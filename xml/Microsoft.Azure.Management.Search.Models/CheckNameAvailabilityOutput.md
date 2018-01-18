<Type Name="CheckNameAvailabilityOutput" FullName="Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput">
  <TypeSignature Language="C#" Value="public class CheckNameAvailabilityOutput" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CheckNameAvailabilityOutput extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput" />
  <TypeSignature Language="VB.NET" Value="Public Class CheckNameAvailabilityOutput" />
  <TypeSignature Language="F#" Value="type CheckNameAvailabilityOutput = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f7767-101">Überprüfen der Verfügbarkeit des Name-API-Ausgabe.</span><span class="sxs-lookup"><span data-stu-id="f7767-101">Output of check name availability API.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckNameAvailabilityOutput ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f7767-102">Initialisiert eine neue Instanz der CheckNameAvailabilityOutput-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f7767-102">Initializes a new instance of the CheckNameAvailabilityOutput class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckNameAvailabilityOutput (Nullable&lt;bool&gt; isNameAvailable = null, string reason = null, string message = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; isNameAvailable, string reason, string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput.#ctor(System.Nullable{System.Boolean},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional isNameAvailable As Nullable(Of Boolean) = null, Optional reason As String = null, Optional message As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput : Nullable&lt;bool&gt; * string * string -&gt; Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput" Usage="new Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput (isNameAvailable, reason, message)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="isNameAvailable" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="reason" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="isNameAvailable"><span data-ttu-id="f7767-103">Ein Wert, der angibt, ob der Name verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="f7767-103">A value indicating whether the name is available.</span></span></param>
        <param name="reason"><span data-ttu-id="f7767-104">Der Grund, warum der Name nicht verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="f7767-104">The reason why the name is not available.</span></span>
            <span data-ttu-id="f7767-105">"Ungültig" gibt an, dass der angegebene Name nicht den benennungsanforderungen (falsche Länge, nicht unterstützte Zeichen usw.) übereinstimmt.</span><span class="sxs-lookup"><span data-stu-id="f7767-105">'Invalid' indicates the name provided does not match the naming requirements (incorrect length, unsupported characters, etc.).</span></span>
            <span data-ttu-id="f7767-106">"AlreadyExists" gibt an, dass der Name bereits verwendet wird und daher nicht verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="f7767-106">'AlreadyExists' indicates that the name is already in use and is therefore unavailable.</span></span> <span data-ttu-id="f7767-107">Folgende Werte sind möglich: "Ungültig", "AlreadyExists"</span><span class="sxs-lookup"><span data-stu-id="f7767-107">Possible values include: 'Invalid', 'AlreadyExists'</span></span></param>
        <param name="message"><span data-ttu-id="f7767-108">Eine Meldung, die erklärt, warum der Name ist ungültig, und detaillierte benennungsanforderungen Ressource.</span><span class="sxs-lookup"><span data-stu-id="f7767-108">A message that explains why the name is invalid and provides resource naming requirements.</span></span> <span data-ttu-id="f7767-109">Verfügbar nur, wenn "Ungültig" in der Eigenschaft "Reason" zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="f7767-109">Available only if 'Invalid' is returned in the 'reason' property.</span></span></param>
        <summary>
            <span data-ttu-id="f7767-110">Initialisiert eine neue Instanz der CheckNameAvailabilityOutput-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f7767-110">Initializes a new instance of the CheckNameAvailabilityOutput class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsNameAvailable">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsNameAvailable { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsNameAvailable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput.IsNameAvailable" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsNameAvailable As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsNameAvailable : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput.IsNameAvailable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nameAvailable")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f7767-111">Ruft einen Wert, der angibt, ob der Name verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="f7767-111">Gets a value indicating whether the name is available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string" Usage="Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
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
            <span data-ttu-id="f7767-112">Ruft eine Meldung, die erklärt, warum der Name ist ungültig, und detaillierte benennungsanforderungen Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="f7767-112">Gets a message that explains why the name is invalid and provides resource naming requirements.</span></span> <span data-ttu-id="f7767-113">Verfügbar nur, wenn "Ungültig" in der Eigenschaft "Reason" zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="f7767-113">Available only if 'Invalid' is returned in the 'reason' property.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Reason">
      <MemberSignature Language="C#" Value="public string Reason { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Reason" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput.Reason" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Reason As String" />
      <MemberSignature Language="F#" Value="member this.Reason : string" Usage="Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput.Reason" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="reason")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f7767-114">Ruft den Grund, warum der Name nicht verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="f7767-114">Gets the reason why the name is not available.</span></span> <span data-ttu-id="f7767-115">"Ungültig" gibt an, dass der angegebene Name nicht den benennungsanforderungen (falsche Länge, nicht unterstützte Zeichen usw.) übereinstimmt.</span><span class="sxs-lookup"><span data-stu-id="f7767-115">'Invalid' indicates the name provided does not match the naming requirements (incorrect length, unsupported characters, etc.).</span></span> <span data-ttu-id="f7767-116">"AlreadyExists" gibt an, dass der Name bereits verwendet wird und daher nicht verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="f7767-116">'AlreadyExists' indicates that the name is already in use and is therefore unavailable.</span></span> <span data-ttu-id="f7767-117">Folgende Werte sind möglich: "Ungültig", "AlreadyExists"</span><span class="sxs-lookup"><span data-stu-id="f7767-117">Possible values include: 'Invalid', 'AlreadyExists'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>