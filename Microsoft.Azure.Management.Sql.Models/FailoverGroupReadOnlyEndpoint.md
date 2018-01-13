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
            Nur-Lese Endpunkt der Gruppeninstanz Failover.
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
            Initialisiert eine neue Instanz der FailoverGroupReadOnlyEndpoint-Klasse.
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
        <param name="failoverPolicy">Failoverrichtlinie für den nur-Lese Endpunkt für die Failover-Gruppe. Folgende Werte sind möglich: "Deaktiviert", "Aktiviert"</param>
        <summary>
            Initialisiert eine neue Instanz der FailoverGroupReadOnlyEndpoint-Klasse.
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
            Ermittelt oder definiert Failoverrichtlinie des nur-Lese Endpunkts für die Failover-Gruppe. Folgende Werte sind möglich: "Deaktiviert", "Aktiviert"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>