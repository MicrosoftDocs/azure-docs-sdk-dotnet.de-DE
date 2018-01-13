<Type Name="FailoverGroupReadWriteEndpoint" FullName="Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint">
  <TypeSignature Language="C#" Value="public class FailoverGroupReadWriteEndpoint" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FailoverGroupReadWriteEndpoint extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint" />
  <TypeSignature Language="VB.NET" Value="Public Class FailoverGroupReadWriteEndpoint" />
  <TypeSignature Language="F#" Value="type FailoverGroupReadWriteEndpoint = class" />
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
            <span data-ttu-id="27f18-101">Lese-/ Schreibzugriff Endpunkt der Gruppeninstanz Failover.</span><span class="sxs-lookup"><span data-stu-id="27f18-101">Read-write endpoint of the failover group instance.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FailoverGroupReadWriteEndpoint ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="27f18-102">Initialisiert eine neue Instanz der FailoverGroupReadWriteEndpoint-Klasse.</span><span class="sxs-lookup"><span data-stu-id="27f18-102">Initializes a new instance of the FailoverGroupReadWriteEndpoint class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FailoverGroupReadWriteEndpoint (string failoverPolicy, Nullable&lt;int&gt; failoverWithDataLossGracePeriodMinutes = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string failoverPolicy, valuetype System.Nullable`1&lt;int32&gt; failoverWithDataLossGracePeriodMinutes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint.#ctor(System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (failoverPolicy As String, Optional failoverWithDataLossGracePeriodMinutes As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint : string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint" Usage="new Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint (failoverPolicy, failoverWithDataLossGracePeriodMinutes)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="failoverPolicy" Type="System.String" />
        <Parameter Name="failoverWithDataLossGracePeriodMinutes" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="failoverPolicy"><span data-ttu-id="27f18-103">Failoverrichtlinie für den Lese-/ Schreibzugriff-Endpunkt für die Failover-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="27f18-103">Failover policy of the read-write endpoint for the failover group.</span></span> <span data-ttu-id="27f18-104">Wenn FailoverPolicy automatisch festgelegt ist, ist FailoverWithDataLossGracePeriodMinutes erforderlich.</span><span class="sxs-lookup"><span data-stu-id="27f18-104">If failoverPolicy is Automatic then failoverWithDataLossGracePeriodMinutes is required.</span></span> <span data-ttu-id="27f18-105">Folgende Werte sind möglich: 'Manual', 'Automatic'</span><span class="sxs-lookup"><span data-stu-id="27f18-105">Possible values include: 'Manual', 'Automatic'</span></span></param>
        <param name="failoverWithDataLossGracePeriodMinutes"><span data-ttu-id="27f18-106">Toleranzperiode vor dem Failover ohne Datenverlust wird versucht, für den Endpunkt Lese-/ Schreibzugriff.</span><span class="sxs-lookup"><span data-stu-id="27f18-106">Grace period before failover with data loss is attempted for the read-write endpoint.</span></span> <span data-ttu-id="27f18-107">Wenn FailoverPolicy automatisch festgelegt ist, ist FailoverWithDataLossGracePeriodMinutes erforderlich.</span><span class="sxs-lookup"><span data-stu-id="27f18-107">If failoverPolicy is Automatic then failoverWithDataLossGracePeriodMinutes is required.</span></span></param>
        <summary>
            <span data-ttu-id="27f18-108">Initialisiert eine neue Instanz der FailoverGroupReadWriteEndpoint-Klasse.</span><span class="sxs-lookup"><span data-stu-id="27f18-108">Initializes a new instance of the FailoverGroupReadWriteEndpoint class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailoverPolicy">
      <MemberSignature Language="C#" Value="public string FailoverPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FailoverPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint.FailoverPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property FailoverPolicy As String" />
      <MemberSignature Language="F#" Value="member this.FailoverPolicy : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint.FailoverPolicy" />
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
            <span data-ttu-id="27f18-109">Ruft ab oder legt Failoverrichtlinie für den Lese-/ Schreibzugriff-Endpunkt für die Failover-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="27f18-109">Gets or sets failover policy of the read-write endpoint for the failover group.</span></span> <span data-ttu-id="27f18-110">Wenn FailoverPolicy automatisch festgelegt ist, ist FailoverWithDataLossGracePeriodMinutes erforderlich.</span><span class="sxs-lookup"><span data-stu-id="27f18-110">If failoverPolicy is Automatic then failoverWithDataLossGracePeriodMinutes is required.</span></span> <span data-ttu-id="27f18-111">Folgende Werte sind möglich: 'Manual', 'Automatic'</span><span class="sxs-lookup"><span data-stu-id="27f18-111">Possible values include: 'Manual', 'Automatic'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailoverWithDataLossGracePeriodMinutes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; FailoverWithDataLossGracePeriodMinutes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; FailoverWithDataLossGracePeriodMinutes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint.FailoverWithDataLossGracePeriodMinutes" />
      <MemberSignature Language="VB.NET" Value="Public Property FailoverWithDataLossGracePeriodMinutes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.FailoverWithDataLossGracePeriodMinutes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint.FailoverWithDataLossGracePeriodMinutes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="failoverWithDataLossGracePeriodMinutes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="27f18-112">Ruft ab, oder legt ihn fest Toleranzperiode vor dem Failover mit Verlust von Daten für den Lese-/ Schreibzugriff Endpunkt versucht wird.</span><span class="sxs-lookup"><span data-stu-id="27f18-112">Gets or sets grace period before failover with data loss is attempted for the read-write endpoint.</span></span> <span data-ttu-id="27f18-113">Wenn FailoverPolicy automatisch festgelegt ist, ist FailoverWithDataLossGracePeriodMinutes erforderlich.</span><span class="sxs-lookup"><span data-stu-id="27f18-113">If failoverPolicy is Automatic then failoverWithDataLossGracePeriodMinutes is required.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="failoverGroupReadWriteEndpoint.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="27f18-114">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="27f18-114">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="27f18-115">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="27f18-115">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>