<Type Name="CheckNameAvailabilityResponse" FullName="Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityResponse">
  <TypeSignature Language="C#" Value="public class CheckNameAvailabilityResponse" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CheckNameAvailabilityResponse extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityResponse" />
  <TypeSignature Language="VB.NET" Value="Public Class CheckNameAvailabilityResponse" />
  <TypeSignature Language="F#" Value="type CheckNameAvailabilityResponse = class" />
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
            <span data-ttu-id="6a712-101">Eine Antwort gibt an, ob der angegebene Name für eine Ressource verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="6a712-101">A response indicating whether the specified name for a resource is available.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckNameAvailabilityResponse ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityResponse.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6a712-102">Initialisiert eine neue Instanz der CheckNameAvailabilityResponse-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6a712-102">Initializes a new instance of the CheckNameAvailabilityResponse class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckNameAvailabilityResponse (Nullable&lt;bool&gt; available = null, string message = null, string name = null, Nullable&lt;Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityReason&gt; reason = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; available, string message, string name, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityReason&gt; reason) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityResponse.#ctor(System.Nullable{System.Boolean},System.String,System.String,System.Nullable{Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityReason})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional available As Nullable(Of Boolean) = null, Optional message As String = null, Optional name As String = null, Optional reason As Nullable(Of CheckNameAvailabilityReason) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityResponse : Nullable&lt;bool&gt; * string * string * Nullable&lt;Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityReason&gt; -&gt; Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityResponse" Usage="new Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityResponse (available, message, name, reason)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="available" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="reason" Type="System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityReason&gt;" />
      </Parameters>
      <Docs>
        <param name="available"><span data-ttu-id="6a712-103">"True", wenn der Name verfügbar, andernfalls "false ist".</span><span class="sxs-lookup"><span data-stu-id="6a712-103">True if the name is available, otherwise false.</span></span></param>
        <param name="message"><span data-ttu-id="6a712-104">Eine Meldung, die erläutern, warum der Name nicht verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="6a712-104">A message explaining why the name is unavailable.</span></span> <span data-ttu-id="6a712-105">Wird null sein, wenn der Name verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="6a712-105">Will be null if the name is available.</span></span></param>
        <param name="name"><span data-ttu-id="6a712-106">Der Name, deren Verfügbarkeit überprüft wurde.</span><span class="sxs-lookup"><span data-stu-id="6a712-106">The name whose availability was checked.</span></span></param>
        <param name="reason"><span data-ttu-id="6a712-107">Der Ursachencode erläutern, warum der Name nicht verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="6a712-107">The reason code explaining why the name is unavailable.</span></span> <span data-ttu-id="6a712-108">Wird null sein, wenn der Name verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="6a712-108">Will be null if the name is available.</span></span> <span data-ttu-id="6a712-109">Folgende Werte sind möglich: "Ungültig", "AlreadyExists"</span><span class="sxs-lookup"><span data-stu-id="6a712-109">Possible values include: 'Invalid', 'AlreadyExists'</span></span></param>
        <summary>
            <span data-ttu-id="6a712-110">Initialisiert eine neue Instanz der CheckNameAvailabilityResponse-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6a712-110">Initializes a new instance of the CheckNameAvailabilityResponse class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Available">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Available { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Available" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityResponse.Available" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Available As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Available : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityResponse.Available" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="available")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6a712-111">Ruft "true", wenn der Name verfügbar, andernfalls "false ist".</span><span class="sxs-lookup"><span data-stu-id="6a712-111">Gets true if the name is available, otherwise false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityResponse.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string" Usage="Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityResponse.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="message")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6a712-112">Ruft eine Meldung, die erläutern, warum der Name nicht verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="6a712-112">Gets a message explaining why the name is unavailable.</span></span> <span data-ttu-id="6a712-113">Wird null sein, wenn der Name verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="6a712-113">Will be null if the name is available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityResponse.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityResponse.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6a712-114">Ruft den Namen ab, deren Verfügbarkeit überprüft wurde.</span><span class="sxs-lookup"><span data-stu-id="6a712-114">Gets the name whose availability was checked.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Reason">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityReason&gt; Reason { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityReason&gt; Reason" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityResponse.Reason" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Reason As Nullable(Of CheckNameAvailabilityReason)" />
      <MemberSignature Language="F#" Value="member this.Reason : Nullable&lt;Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityReason&gt;" Usage="Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityResponse.Reason" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="reason")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityReason&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6a712-115">Ruft den Ursachencode erläutern, warum der Name nicht verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="6a712-115">Gets the reason code explaining why the name is unavailable.</span></span> <span data-ttu-id="6a712-116">Wird null sein, wenn der Name verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="6a712-116">Will be null if the name is available.</span></span> <span data-ttu-id="6a712-117">Folgende Werte sind möglich: "Ungültig", "AlreadyExists"</span><span class="sxs-lookup"><span data-stu-id="6a712-117">Possible values include: 'Invalid', 'AlreadyExists'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>