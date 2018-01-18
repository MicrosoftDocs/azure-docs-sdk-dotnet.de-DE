<Type Name="FailoverGroupReadOnlyEndpoint" FullName="Microsoft.Azure.Management.Sql.Models.FailoverGroupReadOnlyEndpoint">
  <TypeSignature Language="C#" Value="public class FailoverGroupReadOnlyEndpoint" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FailoverGroupReadOnlyEndpoint extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.FailoverGroupReadOnlyEndpoint" />
  <TypeSignature Language="VB.NET" Value="Public Class FailoverGroupReadOnlyEndpoint" />
  <TypeSignature Language="F#" Value="type FailoverGroupReadOnlyEndpoint = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="20ecf-101">Nur-Lese Endpunkt der Gruppeninstanz Failover.</span><span class="sxs-lookup"><span data-stu-id="20ecf-101">Read-only endpoint of the failover group instance.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FailoverGroupReadOnlyEndpoint ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.FailoverGroupReadOnlyEndpoint.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="20ecf-102">Initialisiert eine neue Instanz der FailoverGroupReadOnlyEndpoint-Klasse.</span><span class="sxs-lookup"><span data-stu-id="20ecf-102">Initializes a new instance of the FailoverGroupReadOnlyEndpoint class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FailoverGroupReadOnlyEndpoint (string failoverPolicy = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string failoverPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.FailoverGroupReadOnlyEndpoint.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional failoverPolicy As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.FailoverGroupReadOnlyEndpoint : string -&gt; Microsoft.Azure.Management.Sql.Models.FailoverGroupReadOnlyEndpoint" Usage="new Microsoft.Azure.Management.Sql.Models.FailoverGroupReadOnlyEndpoint failoverPolicy" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="failoverPolicy" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="failoverPolicy"><span data-ttu-id="20ecf-103">Failoverrichtlinie für den nur-Lese Endpunkt für die Failover-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="20ecf-103">Failover policy of the read-only endpoint for the failover group.</span></span> <span data-ttu-id="20ecf-104">Folgende Werte sind möglich: "Deaktiviert", "Aktiviert"</span><span class="sxs-lookup"><span data-stu-id="20ecf-104">Possible values include: 'Disabled', 'Enabled'</span></span></param>
        <summary>
            <span data-ttu-id="20ecf-105">Initialisiert eine neue Instanz der FailoverGroupReadOnlyEndpoint-Klasse.</span><span class="sxs-lookup"><span data-stu-id="20ecf-105">Initializes a new instance of the FailoverGroupReadOnlyEndpoint class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailoverPolicy">
      <MemberSignature Language="C#" Value="public string FailoverPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FailoverPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.FailoverGroupReadOnlyEndpoint.FailoverPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property FailoverPolicy As String" />
      <MemberSignature Language="F#" Value="member this.FailoverPolicy : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.FailoverGroupReadOnlyEndpoint.FailoverPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="failoverPolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="20ecf-106">Ermittelt oder definiert Failoverrichtlinie des nur-Lese Endpunkts für die Failover-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="20ecf-106">Gets or sets failover policy of the read-only endpoint for the failover group.</span></span> <span data-ttu-id="20ecf-107">Folgende Werte sind möglich: "Deaktiviert", "Aktiviert"</span><span class="sxs-lookup"><span data-stu-id="20ecf-107">Possible values include: 'Disabled', 'Enabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>