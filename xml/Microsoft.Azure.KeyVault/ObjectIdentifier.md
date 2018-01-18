<Type Name="ObjectIdentifier" FullName="Microsoft.Azure.KeyVault.ObjectIdentifier">
  <TypeSignature Language="C#" Value="public class ObjectIdentifier" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ObjectIdentifier extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.ObjectIdentifier" />
  <TypeSignature Language="VB.NET" Value="Public Class ObjectIdentifier" />
  <TypeSignature Language="F#" Value="type ObjectIdentifier = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d84e3-101">Der Bezeichner des Key Vault-Objekt.</span><span class="sxs-lookup"><span data-stu-id="d84e3-101">The Key Vault object identifier.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ObjectIdentifier ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.ObjectIdentifier.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d84e3-102">Konstruktor.</span><span class="sxs-lookup"><span data-stu-id="d84e3-102">Constructor.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ObjectIdentifier (string collection, string identifier);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(string collection, string identifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.ObjectIdentifier.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (collection As String, identifier As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.ObjectIdentifier : string * string -&gt; Microsoft.Azure.KeyVault.ObjectIdentifier" Usage="new Microsoft.Azure.KeyVault.ObjectIdentifier (collection, identifier)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="collection" Type="System.String" />
        <Parameter Name="identifier" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="collection"><span data-ttu-id="d84e3-103">die Objektsammlung z. B. "Keys", "geheime Schlüssel" und "Zertifikate".</span><span class="sxs-lookup"><span data-stu-id="d84e3-103">The object collection e.g. 'keys', 'secrets' and 'certificates'.</span></span></param>
        <param name="identifier"><span data-ttu-id="d84e3-104">Der Bezeichner für den schlüsseltresor-Objekt.</span><span class="sxs-lookup"><span data-stu-id="d84e3-104">The key vault object identifier.</span></span></param>
        <summary>
            <span data-ttu-id="d84e3-105">Konstruktor.</span><span class="sxs-lookup"><span data-stu-id="d84e3-105">Constructor.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ObjectIdentifier (string vaultBaseUrl, string collection, string name, string version = &quot;&quot;);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(string vaultBaseUrl, string collection, string name, string version) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.ObjectIdentifier.#ctor(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (vaultBaseUrl As String, collection As String, name As String, Optional version As String = &quot;&quot;)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.ObjectIdentifier : string * string * string * string -&gt; Microsoft.Azure.KeyVault.ObjectIdentifier" Usage="new Microsoft.Azure.KeyVault.ObjectIdentifier (vaultBaseUrl, collection, name, version)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="collection" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl"> <span data-ttu-id="d84e3-106">Die Vault-Basis-URL</span><span class="sxs-lookup"><span data-stu-id="d84e3-106">The vault base URL</span></span></param>
        <param name="collection"><span data-ttu-id="d84e3-107">die Objektsammlung z. B. "Keys", "geheime Schlüssel" und "Zertifikate".</span><span class="sxs-lookup"><span data-stu-id="d84e3-107">The object collection e.g. 'keys', 'secrets' and 'certificates'.</span></span></param>
        <param name="name"><span data-ttu-id="d84e3-108">Der Objektname.</span><span class="sxs-lookup"><span data-stu-id="d84e3-108">The object name.</span></span></param>
        <param name="version"> <span data-ttu-id="d84e3-109">Die Version des Objekts.</span><span class="sxs-lookup"><span data-stu-id="d84e3-109">the version of the object.</span></span></param>
        <summary>
            <span data-ttu-id="d84e3-110">Konstruktor.</span><span class="sxs-lookup"><span data-stu-id="d84e3-110">Constructor.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseIdentifier">
      <MemberSignature Language="C#" Value="public string BaseIdentifier { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BaseIdentifier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.ObjectIdentifier.BaseIdentifier" />
      <MemberSignature Language="VB.NET" Value="Public Property BaseIdentifier As String" />
      <MemberSignature Language="F#" Value="member this.BaseIdentifier : string with get, set" Usage="Microsoft.Azure.KeyVault.ObjectIdentifier.BaseIdentifier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d84e3-111">Die base-ID für ein Objekt umfasst nicht die Objektversion.</span><span class="sxs-lookup"><span data-stu-id="d84e3-111">The base identifier for an object, does not include the object version.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Identifier">
      <MemberSignature Language="C#" Value="public string Identifier { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Identifier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.ObjectIdentifier.Identifier" />
      <MemberSignature Language="VB.NET" Value="Public Property Identifier As String" />
      <MemberSignature Language="F#" Value="member this.Identifier : string with get, set" Usage="Microsoft.Azure.KeyVault.ObjectIdentifier.Identifier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d84e3-112">Der Bezeichner für ein Objekt enthält die Objekte-Version.</span><span class="sxs-lookup"><span data-stu-id="d84e3-112">The identifier for an object, includes the objects version.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsObjectIdentifier">
      <MemberSignature Language="C#" Value="protected static bool IsObjectIdentifier (string collection, string identifier);" />
      <MemberSignature Language="ILAsm" Value=".method familystatic hidebysig bool IsObjectIdentifier(string collection, string identifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.ObjectIdentifier.IsObjectIdentifier(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Shared Function IsObjectIdentifier (collection As String, identifier As String) As Boolean" />
      <MemberSignature Language="F#" Value="static member IsObjectIdentifier : string * string -&gt; bool" Usage="Microsoft.Azure.KeyVault.ObjectIdentifier.IsObjectIdentifier (collection, identifier)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collection" Type="System.String" />
        <Parameter Name="identifier" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="collection"><span data-ttu-id="d84e3-113">die Objektsammlung z. B. "Keys", "geheime Schlüssel" und "Zertifikate".</span><span class="sxs-lookup"><span data-stu-id="d84e3-113">The object collection e.g. 'keys', 'secrets' and 'certificates'.</span></span></param>
        <param name="identifier"><span data-ttu-id="d84e3-114">Der Bezeichner für den schlüsseltresor-Objekt.</span><span class="sxs-lookup"><span data-stu-id="d84e3-114">The key vault object identifier.</span></span></param>
        <summary>
            <span data-ttu-id="d84e3-115">Überprüft, ob der Bezeichner mit einem Key Vault-Objekt gehört.</span><span class="sxs-lookup"><span data-stu-id="d84e3-115">Verifies whether the identifier belongs to a key vault object.</span></span>
            </summary>
        <returns><span data-ttu-id="d84e3-116">"true", wenn der Bezeichner mit einem Key Vault-Objekt gehört.</span><span class="sxs-lookup"><span data-stu-id="d84e3-116">True if the identifier belongs to a key vault object.</span></span> <span data-ttu-id="d84e3-117">"False" andernfalls.</span><span class="sxs-lookup"><span data-stu-id="d84e3-117">False otherwise.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.ObjectIdentifier.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.KeyVault.ObjectIdentifier.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d84e3-118">Der Name des Objekts.</span><span class="sxs-lookup"><span data-stu-id="d84e3-118">The name of the object.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.ObjectIdentifier.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="objectIdentifier.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Vault">
      <MemberSignature Language="C#" Value="public string Vault { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Vault" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.ObjectIdentifier.Vault" />
      <MemberSignature Language="VB.NET" Value="Public Property Vault As String" />
      <MemberSignature Language="F#" Value="member this.Vault : string with get, set" Usage="Microsoft.Azure.KeyVault.ObjectIdentifier.Vault" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d84e3-119">Den Tresor, der das Objekt enthält</span><span class="sxs-lookup"><span data-stu-id="d84e3-119">The vault containing the object</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VaultWithoutScheme">
      <MemberSignature Language="C#" Value="public string VaultWithoutScheme { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VaultWithoutScheme" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.ObjectIdentifier.VaultWithoutScheme" />
      <MemberSignature Language="VB.NET" Value="Public Property VaultWithoutScheme As String" />
      <MemberSignature Language="F#" Value="member this.VaultWithoutScheme : string with get, set" Usage="Microsoft.Azure.KeyVault.ObjectIdentifier.VaultWithoutScheme" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d84e3-120">Die URL-Schema-kleiner Tresor</span><span class="sxs-lookup"><span data-stu-id="d84e3-120">The scheme-less vault URL</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public string Version { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.ObjectIdentifier.Version" />
      <MemberSignature Language="VB.NET" Value="Public Property Version As String" />
      <MemberSignature Language="F#" Value="member this.Version : string with get, set" Usage="Microsoft.Azure.KeyVault.ObjectIdentifier.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d84e3-121">Die Version des Objekts.</span><span class="sxs-lookup"><span data-stu-id="d84e3-121">The version of the object.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>