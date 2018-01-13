<Type Name="ExportRequest" FullName="Microsoft.Azure.Management.Sql.Models.ExportRequest">
  <TypeSignature Language="C#" Value="public class ExportRequest" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExportRequest extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.ExportRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class ExportRequest" />
  <TypeSignature Language="F#" Value="type ExportRequest = class" />
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
            <span data-ttu-id="25335-101">Exportieren Sie die Datenbankparameter.</span><span class="sxs-lookup"><span data-stu-id="25335-101">Export database parameters.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExportRequest ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ExportRequest.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="25335-102">Initialisiert eine neue Instanz der ExportRequest-Klasse.</span><span class="sxs-lookup"><span data-stu-id="25335-102">Initializes a new instance of the ExportRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExportRequest (Microsoft.Azure.Management.Sql.Models.StorageKeyType storageKeyType, string storageKey, string storageUri, string administratorLogin, string administratorLoginPassword, Nullable&lt;Microsoft.Azure.Management.Sql.Models.AuthenticationType&gt; authenticationType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.Sql.Models.StorageKeyType storageKeyType, string storageKey, string storageUri, string administratorLogin, string administratorLoginPassword, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.AuthenticationType&gt; authenticationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ExportRequest.#ctor(Microsoft.Azure.Management.Sql.Models.StorageKeyType,System.String,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.Sql.Models.AuthenticationType})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.ExportRequest : Microsoft.Azure.Management.Sql.Models.StorageKeyType * string * string * string * string * Nullable&lt;Microsoft.Azure.Management.Sql.Models.AuthenticationType&gt; -&gt; Microsoft.Azure.Management.Sql.Models.ExportRequest" Usage="new Microsoft.Azure.Management.Sql.Models.ExportRequest (storageKeyType, storageKey, storageUri, administratorLogin, administratorLoginPassword, authenticationType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageKeyType" Type="Microsoft.Azure.Management.Sql.Models.StorageKeyType" />
        <Parameter Name="storageKey" Type="System.String" />
        <Parameter Name="storageUri" Type="System.String" />
        <Parameter Name="administratorLogin" Type="System.String" />
        <Parameter Name="administratorLoginPassword" Type="System.String" />
        <Parameter Name="authenticationType" Type="System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.AuthenticationType&gt;" />
      </Parameters>
      <Docs>
        <param name="storageKeyType"><span data-ttu-id="25335-103">Der Typ des speicherschlüssels zu verwenden.</span><span class="sxs-lookup"><span data-stu-id="25335-103">The type of the storage key to use.</span></span>
            <span data-ttu-id="25335-104">Folgende Werte sind möglich: "StorageAccessKey", "SharedAccessKey"</span><span class="sxs-lookup"><span data-stu-id="25335-104">Possible values include: 'StorageAccessKey', 'SharedAccessKey'</span></span></param>
        <param name="storageKey"><span data-ttu-id="25335-105">Der Speicherschlüssel verwenden.</span><span class="sxs-lookup"><span data-stu-id="25335-105">The storage key to use.</span></span>  <span data-ttu-id="25335-106">Wenn Speicher Schlüsseltyp SharedAccessKey ist, muss er mit stehen ein "?."</span><span class="sxs-lookup"><span data-stu-id="25335-106">If storage key type is SharedAccessKey, it must be preceded with a "?."</span></span></param>
        <param name="storageUri"><span data-ttu-id="25335-107">Der Speicher-Uri, der verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="25335-107">The storage uri to use.</span></span></param>
        <param name="administratorLogin"><span data-ttu-id="25335-108">Der Name der SQL-Administrator.</span><span class="sxs-lookup"><span data-stu-id="25335-108">The name of the SQL administrator.</span></span></param>
        <param name="administratorLoginPassword"><span data-ttu-id="25335-109">Das Kennwort des SQL-Administrator.</span><span class="sxs-lookup"><span data-stu-id="25335-109">The password of the SQL administrator.</span></span></param>
        <param name="authenticationType"><span data-ttu-id="25335-110">Der Authentifizierungstyp.</span><span class="sxs-lookup"><span data-stu-id="25335-110">The authentication type.</span></span> <span data-ttu-id="25335-111">Folgende Werte sind möglich: 'SQL', 'ADPassword'</span><span class="sxs-lookup"><span data-stu-id="25335-111">Possible values include: 'SQL', 'ADPassword'</span></span></param>
        <summary>
            <span data-ttu-id="25335-112">Initialisiert eine neue Instanz der ExportRequest-Klasse.</span><span class="sxs-lookup"><span data-stu-id="25335-112">Initializes a new instance of the ExportRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdministratorLogin">
      <MemberSignature Language="C#" Value="public string AdministratorLogin { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AdministratorLogin" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ExportRequest.AdministratorLogin" />
      <MemberSignature Language="VB.NET" Value="Public Property AdministratorLogin As String" />
      <MemberSignature Language="F#" Value="member this.AdministratorLogin : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.ExportRequest.AdministratorLogin" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="administratorLogin")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="25335-113">Ruft ab oder legt den Namen der SQL-Administrator.</span><span class="sxs-lookup"><span data-stu-id="25335-113">Gets or sets the name of the SQL administrator.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdministratorLoginPassword">
      <MemberSignature Language="C#" Value="public string AdministratorLoginPassword { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AdministratorLoginPassword" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ExportRequest.AdministratorLoginPassword" />
      <MemberSignature Language="VB.NET" Value="Public Property AdministratorLoginPassword As String" />
      <MemberSignature Language="F#" Value="member this.AdministratorLoginPassword : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.ExportRequest.AdministratorLoginPassword" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="administratorLoginPassword")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="25335-114">Ruft ab oder legt das Kennwort des SQL-Administrator.</span><span class="sxs-lookup"><span data-stu-id="25335-114">Gets or sets the password of the SQL administrator.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Sql.Models.AuthenticationType&gt; AuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.AuthenticationType&gt; AuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ExportRequest.AuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationType As Nullable(Of AuthenticationType)" />
      <MemberSignature Language="F#" Value="member this.AuthenticationType : Nullable&lt;Microsoft.Azure.Management.Sql.Models.AuthenticationType&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.ExportRequest.AuthenticationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="authenticationType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.AuthenticationType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="25335-115">Ruft ab oder legt den Authentifizierungstyp.</span><span class="sxs-lookup"><span data-stu-id="25335-115">Gets or sets the authentication type.</span></span> <span data-ttu-id="25335-116">Folgende Werte sind möglich: 'SQL', 'ADPassword'</span><span class="sxs-lookup"><span data-stu-id="25335-116">Possible values include: 'SQL', 'ADPassword'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageKey">
      <MemberSignature Language="C#" Value="public string StorageKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ExportRequest.StorageKey" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageKey As String" />
      <MemberSignature Language="F#" Value="member this.StorageKey : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.ExportRequest.StorageKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="25335-117">Ruft ab, oder legt ihn fest Speicherschlüssel verwenden.</span><span class="sxs-lookup"><span data-stu-id="25335-117">Gets or sets the storage key to use.</span></span>  <span data-ttu-id="25335-118">Wenn Speicher Schlüsseltyp SharedAccessKey ist, muss er mit stehen ein "?."</span><span class="sxs-lookup"><span data-stu-id="25335-118">If storage key type is SharedAccessKey, it must be preceded with a "?."</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageKeyType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Models.StorageKeyType StorageKeyType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Sql.Models.StorageKeyType StorageKeyType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ExportRequest.StorageKeyType" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageKeyType As StorageKeyType" />
      <MemberSignature Language="F#" Value="member this.StorageKeyType : Microsoft.Azure.Management.Sql.Models.StorageKeyType with get, set" Usage="Microsoft.Azure.Management.Sql.Models.ExportRequest.StorageKeyType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageKeyType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.StorageKeyType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="25335-119">Ruft ab oder legt den Typ des speicherschlüssels zu verwenden.</span><span class="sxs-lookup"><span data-stu-id="25335-119">Gets or sets the type of the storage key to use.</span></span> <span data-ttu-id="25335-120">Folgende Werte sind möglich: "StorageAccessKey", "SharedAccessKey"</span><span class="sxs-lookup"><span data-stu-id="25335-120">Possible values include: 'StorageAccessKey', 'SharedAccessKey'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageUri">
      <MemberSignature Language="C#" Value="public string StorageUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ExportRequest.StorageUri" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageUri As String" />
      <MemberSignature Language="F#" Value="member this.StorageUri : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.ExportRequest.StorageUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="25335-121">Ruft ab oder legt die Speicher-Uri, der verwendet.</span><span class="sxs-lookup"><span data-stu-id="25335-121">Gets or sets the storage uri to use.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ExportRequest.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="exportRequest.Validate " />
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
            <span data-ttu-id="25335-122">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="25335-122">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="25335-123">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="25335-123">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>