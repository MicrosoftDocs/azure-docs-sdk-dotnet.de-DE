<Type Name="StorageCredentials" FullName="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials">
  <TypeSignature Language="C#" Value="public sealed class StorageCredentials" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit StorageCredentials extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class StorageCredentials" />
  <TypeSignature Language="F#" Value="type StorageCredentials = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="92b46-101">Stellt einen Satz von Anmeldeinformationen zum Authentifizieren des Zugriffs auf ein Microsoft Azure Storage-Konto verwendet.</span><span class="sxs-lookup"><span data-stu-id="92b46-101">Represents a set of credentials used to authenticate access to a Microsoft Azure storage account.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageCredentials ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="92b46-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="92b46-102">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageCredentials (string sasToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string sasToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (sasToken As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Auth.StorageCredentials : string -&gt; Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" Usage="new Microsoft.WindowsAzure.Storage.Auth.StorageCredentials sasToken" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sasToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sasToken"><span data-ttu-id="92b46-103">Eine Zeichenfolge, die die SAS-Token darstellt.</span><span class="sxs-lookup"><span data-stu-id="92b46-103">A string representing the shared access signature token.</span></span></param>
        <summary>
            <span data-ttu-id="92b46-104">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> Klasse mit dem angegebenen freigegebenen SAS-Token.</span><span class="sxs-lookup"><span data-stu-id="92b46-104">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> class with the specified shared access signature token.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageCredentials (string accountName, byte[] keyValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string accountName, unsigned int8[] keyValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.#ctor(System.String,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (accountName As String, keyValue As Byte())" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Auth.StorageCredentials : string * byte[] -&gt; Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" Usage="new Microsoft.WindowsAzure.Storage.Auth.StorageCredentials (accountName, keyValue)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="keyValue" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="accountName"><span data-ttu-id="92b46-105">Eine Zeichenfolge, die den Namen des Speicherkontos darstellt.</span><span class="sxs-lookup"><span data-stu-id="92b46-105">A string that represents the name of the storage account.</span></span></param>
        <param name="keyValue"><span data-ttu-id="92b46-106">Ein Array von Bytes, die den kontozugriffsschlüssel darstellen.</span><span class="sxs-lookup"><span data-stu-id="92b46-106">An array of bytes that represent the account access key.</span></span></param>
        <summary>
            <span data-ttu-id="92b46-107">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> Klasse mit dem angegebenen Kontonamen und Schlüsselwert.</span><span class="sxs-lookup"><span data-stu-id="92b46-107">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> class with the specified account name and key value.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageCredentials (string accountName, string keyValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string accountName, string keyValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (accountName As String, keyValue As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Auth.StorageCredentials : string * string -&gt; Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" Usage="new Microsoft.WindowsAzure.Storage.Auth.StorageCredentials (accountName, keyValue)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="keyValue" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="accountName"><span data-ttu-id="92b46-108">Eine Zeichenfolge, die den Namen des Speicherkontos darstellt.</span><span class="sxs-lookup"><span data-stu-id="92b46-108">A string that represents the name of the storage account.</span></span></param>
        <param name="keyValue"><span data-ttu-id="92b46-109">Eine Zeichenfolge, die Base64-codierten kontozugriffsschlüssel darstellt.</span><span class="sxs-lookup"><span data-stu-id="92b46-109">A string that represents the Base64-encoded account access key.</span></span></param>
        <summary>
            <span data-ttu-id="92b46-110">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> Klasse mit dem angegebenen Kontonamen und Schlüsselwert.</span><span class="sxs-lookup"><span data-stu-id="92b46-110">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> class with the specified account name and key value.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageCredentials (string accountName, byte[] keyValue, string keyName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string accountName, unsigned int8[] keyValue, string keyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.#ctor(System.String,System.Byte[],System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (accountName As String, keyValue As Byte(), keyName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Auth.StorageCredentials : string * byte[] * string -&gt; Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" Usage="new Microsoft.WindowsAzure.Storage.Auth.StorageCredentials (accountName, keyValue, keyName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="keyValue" Type="System.Byte[]" />
        <Parameter Name="keyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="accountName"><span data-ttu-id="92b46-111">Eine Zeichenfolge, die den Namen des Speicherkontos darstellt.</span><span class="sxs-lookup"><span data-stu-id="92b46-111">A string that represents the name of the storage account.</span></span></param>
        <param name="keyValue"><span data-ttu-id="92b46-112">Ein Array von Bytes, die den kontozugriffsschlüssel darstellen.</span><span class="sxs-lookup"><span data-stu-id="92b46-112">An array of bytes that represent the account access key.</span></span></param>
        <param name="keyName"><span data-ttu-id="92b46-113">Eine Zeichenfolge, die den Namen des Schlüssels darstellt.</span><span class="sxs-lookup"><span data-stu-id="92b46-113">A string that represents the name of the key.</span></span></param>
        <summary>
            <span data-ttu-id="92b46-114">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> -Klasse mit dem angegebenen Kontonamen ein, die Schlüssel-Wert und den Schlüsselnamen.</span><span class="sxs-lookup"><span data-stu-id="92b46-114">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> class with the specified account name, key value, and key name.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageCredentials (string accountName, string keyValue, string keyName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string accountName, string keyValue, string keyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (accountName As String, keyValue As String, keyName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Auth.StorageCredentials : string * string * string -&gt; Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" Usage="new Microsoft.WindowsAzure.Storage.Auth.StorageCredentials (accountName, keyValue, keyName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="keyValue" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="accountName"><span data-ttu-id="92b46-115">Eine Zeichenfolge, die den Namen des Speicherkontos darstellt.</span><span class="sxs-lookup"><span data-stu-id="92b46-115">A string that represents the name of the storage account.</span></span></param>
        <param name="keyValue"><span data-ttu-id="92b46-116">Eine Zeichenfolge, die Base64-codierten kontozugriffsschlüssel darstellt.</span><span class="sxs-lookup"><span data-stu-id="92b46-116">A string that represents the Base64-encoded account access key.</span></span></param>
        <param name="keyName"><span data-ttu-id="92b46-117">Eine Zeichenfolge, die den Namen des Schlüssels darstellt.</span><span class="sxs-lookup"><span data-stu-id="92b46-117">A string that represents the name of the key.</span></span></param>
        <summary>
            <span data-ttu-id="92b46-118">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> -Klasse mit dem angegebenen Kontonamen ein, die Schlüssel-Wert und den Schlüsselnamen.</span><span class="sxs-lookup"><span data-stu-id="92b46-118">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> class with the specified account name, key value, and key name.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountName">
      <MemberSignature Language="C#" Value="public string AccountName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccountName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.AccountName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccountName As String" />
      <MemberSignature Language="F#" Value="member this.AccountName : string" Usage="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.AccountName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="92b46-119">Ruft den zugeordneten Kontonamen für die Anmeldeinformationen ab.</span><span class="sxs-lookup"><span data-stu-id="92b46-119">Gets the associated account name for the credentials.</span></span>
            </summary>
        <value><span data-ttu-id="92b46-120">Der Kontoname.</span><span class="sxs-lookup"><span data-stu-id="92b46-120">The account name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.WindowsAzure.Storage.Auth.StorageCredentials other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool Equals(class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.Equals(Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As StorageCredentials) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; bool" Usage="storageCredentials.Equals other" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />
      </Parameters>
      <Docs>
        <param name="other"><span data-ttu-id="92b46-121">Die <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> zu diesem Objekt zu vergleichende Objekt.</span><span class="sxs-lookup"><span data-stu-id="92b46-121">The <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> object to compare to this one.</span></span></param>
        <summary>
            <span data-ttu-id="92b46-122">Bestimmt, ob ein anderes <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> Objekt gleich dieser Klassifizierung, indem Sie ihre SAS-Token, Kontonamen, Schlüsselnamen und Schlüsselwerte verglichen.</span><span class="sxs-lookup"><span data-stu-id="92b46-122">Determines whether an other <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> object is equal to this one by comparing their SAS tokens, account names, key names, and key values.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="92b46-123"><c>"true"</c> Wenn die beiden <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> Objekte sind gleich sind, andernfalls <c>"false"</c>.</span><span class="sxs-lookup"><span data-stu-id="92b46-123"><c>true</c> if the two <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> objects are equal; otherwise, <c>false</c>.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportBase64EncodedKey">
      <MemberSignature Language="C#" Value="public string ExportBase64EncodedKey ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string ExportBase64EncodedKey() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.ExportBase64EncodedKey" />
      <MemberSignature Language="VB.NET" Value="Public Function ExportBase64EncodedKey () As String" />
      <MemberSignature Language="F#" Value="member this.ExportBase64EncodedKey : unit -&gt; string" Usage="storageCredentials.ExportBase64EncodedKey " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="92b46-124">Exportiert den Wert des Zugriffsschlüssels in eine Base64-codierte Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="92b46-124">Exports the value of the account access key to a Base64-encoded string.</span></span>
            </summary>
        <returns><span data-ttu-id="92b46-125">Der kontozugriffsschlüssel.</span><span class="sxs-lookup"><span data-stu-id="92b46-125">The account access key.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportKey">
      <MemberSignature Language="C#" Value="public byte[] ExportKey ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance unsigned int8[] ExportKey() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.ExportKey" />
      <MemberSignature Language="VB.NET" Value="Public Function ExportKey () As Byte()" />
      <MemberSignature Language="F#" Value="member this.ExportKey : unit -&gt; byte[]" Usage="storageCredentials.ExportKey " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="92b46-126">Gibt den kontoschlüssel für die Anmeldeinformationen an.</span><span class="sxs-lookup"><span data-stu-id="92b46-126">Returns the account key for the credentials.</span></span>
            </summary>
        <returns><span data-ttu-id="92b46-127">Ein Array von Bytes, die den Schlüssel enthält.</span><span class="sxs-lookup"><span data-stu-id="92b46-127">An array of bytes that contains the key.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsAnonymous">
      <MemberSignature Language="C#" Value="public bool IsAnonymous { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsAnonymous" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.IsAnonymous" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsAnonymous As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsAnonymous : bool" Usage="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.IsAnonymous" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="92b46-128">Ruft einen Wert, der angibt, ob die Anmeldeinformationen für den anonymen Zugriff sind.</span><span class="sxs-lookup"><span data-stu-id="92b46-128">Gets a value indicating whether the credentials are for anonymous access.</span></span>
            </summary>
        <value>
          <span data-ttu-id="92b46-129"><c>"true"</c> sind die Anmeldeinformationen für den anonymen Zugriff; andernfalls <c>"false"</c>.</span><span class="sxs-lookup"><span data-stu-id="92b46-129"><c>true</c> if the credentials are for anonymous access; otherwise, <c>false</c>.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsSAS">
      <MemberSignature Language="C#" Value="public bool IsSAS { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsSAS" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.IsSAS" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsSAS As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsSAS : bool" Usage="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.IsSAS" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="92b46-130">Ruft einen Wert, der angibt, ob die Anmeldeinformationen ein SAS-token ab.</span><span class="sxs-lookup"><span data-stu-id="92b46-130">Gets a value indicating whether the credentials are a shared access signature token.</span></span>
            </summary>
        <value>
          <span data-ttu-id="92b46-131"><c>"true"</c> sind die Anmeldeinformationen eine shared Access Signature ist, andernfalls <c>"false"</c>.</span><span class="sxs-lookup"><span data-stu-id="92b46-131"><c>true</c> if the credentials are a shared access signature token; otherwise, <c>false</c>.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsSharedKey">
      <MemberSignature Language="C#" Value="public bool IsSharedKey { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsSharedKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.IsSharedKey" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsSharedKey As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsSharedKey : bool" Usage="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.IsSharedKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="92b46-132">Ruft einen Wert, der angibt, ob die Anmeldeinformationen ein gemeinsam verwendeter Schlüssel sind.</span><span class="sxs-lookup"><span data-stu-id="92b46-132">Gets a value indicating whether the credentials are a shared key.</span></span>
            </summary>
        <value>
          <span data-ttu-id="92b46-133"><c>"true"</c> sind die Anmeldeinformationen einem gemeinsam verwendeten Schlüssel ist, andernfalls <c>"false"</c>.</span><span class="sxs-lookup"><span data-stu-id="92b46-133"><c>true</c> if the credentials are a shared key; otherwise, <c>false</c>.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyName">
      <MemberSignature Language="C#" Value="public string KeyName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.KeyName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property KeyName As String" />
      <MemberSignature Language="F#" Value="member this.KeyName : string" Usage="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.KeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="92b46-134">Ruft den zugeordneten Schlüsselnamen für die Anmeldeinformationen ab.</span><span class="sxs-lookup"><span data-stu-id="92b46-134">Gets the associated key name for the credentials.</span></span>
            </summary>
        <value><span data-ttu-id="92b46-135">Der Schlüsselname.</span><span class="sxs-lookup"><span data-stu-id="92b46-135">The key name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SASSignature">
      <MemberSignature Language="C#" Value="public string SASSignature { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SASSignature" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.SASSignature" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SASSignature As String" />
      <MemberSignature Language="F#" Value="member this.SASSignature : string" Usage="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.SASSignature" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="92b46-136">Ruft den Wert der SAS-Token des <c>Sig</c> Parameter.</span><span class="sxs-lookup"><span data-stu-id="92b46-136">Gets the value of the shared access signature token's <c>sig</c> parameter.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SASToken">
      <MemberSignature Language="C#" Value="public string SASToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SASToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.SASToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SASToken As String" />
      <MemberSignature Language="F#" Value="member this.SASToken : string" Usage="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.SASToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="92b46-137">Ruft das zugeordnete SAS-token für die Anmeldeinformationen ab.</span><span class="sxs-lookup"><span data-stu-id="92b46-137">Gets the associated shared access signature token for the credentials.</span></span>
            </summary>
        <value><span data-ttu-id="92b46-138">Die SAS-Token.</span><span class="sxs-lookup"><span data-stu-id="92b46-138">The shared access signature token.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransformUri">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.StorageUri TransformUri (Microsoft.WindowsAzure.Storage.StorageUri resourceUri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.StorageUri TransformUri(class Microsoft.WindowsAzure.Storage.StorageUri resourceUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.TransformUri(Microsoft.WindowsAzure.Storage.StorageUri)" />
      <MemberSignature Language="VB.NET" Value="Public Function TransformUri (resourceUri As StorageUri) As StorageUri" />
      <MemberSignature Language="F#" Value="member this.TransformUri : Microsoft.WindowsAzure.Storage.StorageUri -&gt; Microsoft.WindowsAzure.Storage.StorageUri" Usage="storageCredentials.TransformUri resourceUri" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.StorageUri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceUri" Type="Microsoft.WindowsAzure.Storage.StorageUri" />
      </Parameters>
      <Docs>
        <param name="resourceUri"><span data-ttu-id="92b46-139">Ein <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> Objekt, das den Ressourcen-URI zu transformierende darstellt.</span><span class="sxs-lookup"><span data-stu-id="92b46-139">A <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> object that represents the resource URI to be transformed.</span></span></param>
        <summary>
            <span data-ttu-id="92b46-140">Transformiert einen Ressourcen-URI in einen SAS-URI durch Anfügen einer SAS-Token.</span><span class="sxs-lookup"><span data-stu-id="92b46-140">Transforms a resource URI into a shared access signature URI, by appending a shared access token.</span></span>
            </summary>
        <returns><span data-ttu-id="92b46-141">Ein <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> Objekt, das die Signatur, einschließlich der Ressourcen-URI und das SAS-Token darstellt.</span><span class="sxs-lookup"><span data-stu-id="92b46-141">A <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> object that represents the signature, including the resource URI and the shared access token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransformUri">
      <MemberSignature Language="C#" Value="public Uri TransformUri (Uri resourceUri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Uri TransformUri(class System.Uri resourceUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.TransformUri(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function TransformUri (resourceUri As Uri) As Uri" />
      <MemberSignature Language="F#" Value="member this.TransformUri : Uri -&gt; Uri" Usage="storageCredentials.TransformUri resourceUri" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceUri" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="resourceUri"><span data-ttu-id="92b46-142">Ein <see cref="T:System.Uri" /> Objekt, das den Ressourcen-URI zu transformierende darstellt.</span><span class="sxs-lookup"><span data-stu-id="92b46-142">A <see cref="T:System.Uri" /> object that represents the resource URI to be transformed.</span></span></param>
        <summary>
            <span data-ttu-id="92b46-143">Transformiert einen Ressourcen-URI in einen SAS-URI durch Anfügen einer SAS-Token.</span><span class="sxs-lookup"><span data-stu-id="92b46-143">Transforms a resource URI into a shared access signature URI, by appending a shared access token.</span></span>
            </summary>
        <returns><span data-ttu-id="92b46-144">Ein <see cref="T:System.Uri" /> Objekt, das die Signatur, einschließlich der Ressourcen-URI und das SAS-Token darstellt.</span><span class="sxs-lookup"><span data-stu-id="92b46-144">A <see cref="T:System.Uri" /> object that represents the signature, including the resource URI and the shared access token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateKey">
      <MemberSignature Language="C#" Value="public void UpdateKey (byte[] keyValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void UpdateKey(unsigned int8[] keyValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.UpdateKey(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub UpdateKey (keyValue As Byte())" />
      <MemberSignature Language="F#" Value="member this.UpdateKey : byte[] -&gt; unit" Usage="storageCredentials.UpdateKey keyValue" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyValue" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="keyValue"><span data-ttu-id="92b46-145">Der Schlüsselwert als Array von Bytes, die Sie aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="92b46-145">The key value, as an array of bytes, to update.</span></span></param>
        <summary>
            <span data-ttu-id="92b46-146">Aktualisiert den Schlüsselwert für die Anmeldeinformationen an.</span><span class="sxs-lookup"><span data-stu-id="92b46-146">Updates the key value for the credentials.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateKey">
      <MemberSignature Language="C#" Value="public void UpdateKey (string keyValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void UpdateKey(string keyValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.UpdateKey(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub UpdateKey (keyValue As String)" />
      <MemberSignature Language="F#" Value="member this.UpdateKey : string -&gt; unit" Usage="storageCredentials.UpdateKey keyValue" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyValue" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="keyValue"><span data-ttu-id="92b46-147">Der Schlüsselwert als Base64-codierte Zeichenfolge, zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="92b46-147">The key value, as a Base64-encoded string, to update.</span></span></param>
        <summary>
            <span data-ttu-id="92b46-148">Aktualisiert den Schlüsselwert für die Anmeldeinformationen an.</span><span class="sxs-lookup"><span data-stu-id="92b46-148">Updates the key value for the credentials.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateKey">
      <MemberSignature Language="C#" Value="public void UpdateKey (byte[] keyValue, string keyName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void UpdateKey(unsigned int8[] keyValue, string keyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.UpdateKey(System.Byte[],System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub UpdateKey (keyValue As Byte(), keyName As String)" />
      <MemberSignature Language="F#" Value="member this.UpdateKey : byte[] * string -&gt; unit" Usage="storageCredentials.UpdateKey (keyValue, keyName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyValue" Type="System.Byte[]" />
        <Parameter Name="keyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="keyValue"><span data-ttu-id="92b46-149">Der Schlüsselwert als Array von Bytes, die Sie aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="92b46-149">The key value, as an array of bytes, to update.</span></span></param>
        <param name="keyName"><span data-ttu-id="92b46-150">Der Schlüsselname zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="92b46-150">The key name to update.</span></span></param>
        <summary>
            <span data-ttu-id="92b46-151">Aktualisiert den Schlüsselwert und die Schlüsselnamen für die Anmeldeinformationen an.</span><span class="sxs-lookup"><span data-stu-id="92b46-151">Updates the key value and key name for the credentials.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateKey">
      <MemberSignature Language="C#" Value="public void UpdateKey (string keyValue, string keyName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void UpdateKey(string keyValue, string keyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.UpdateKey(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub UpdateKey (keyValue As String, keyName As String)" />
      <MemberSignature Language="F#" Value="member this.UpdateKey : string * string -&gt; unit" Usage="storageCredentials.UpdateKey (keyValue, keyName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyValue" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="keyValue"><span data-ttu-id="92b46-152">Der Schlüsselwert als Base64-codierte Zeichenfolge, zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="92b46-152">The key value, as a Base64-encoded string, to update.</span></span></param>
        <param name="keyName"><span data-ttu-id="92b46-153">Der Schlüsselname zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="92b46-153">The key name to update.</span></span></param>
        <summary>
            <span data-ttu-id="92b46-154">Aktualisiert den Schlüsselwert und die Schlüsselnamen für die Anmeldeinformationen an.</span><span class="sxs-lookup"><span data-stu-id="92b46-154">Updates the key value and key name for the credentials.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateSASToken">
      <MemberSignature Language="C#" Value="public void UpdateSASToken (string sasToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void UpdateSASToken(string sasToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.UpdateSASToken(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub UpdateSASToken (sasToken As String)" />
      <MemberSignature Language="F#" Value="member this.UpdateSASToken : string -&gt; unit" Usage="storageCredentials.UpdateSASToken sasToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sasToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sasToken"><span data-ttu-id="92b46-155">Eine Zeichenfolge, die angibt, die SAS-token Wert, der aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="92b46-155">A string that specifies the SAS token value to update.</span></span></param>
        <summary>
            <span data-ttu-id="92b46-156">Aktualisiert den gemeinsamen Zugriff Signature (SAS)-Tokenwert für mit einer SAS erstellten speicheranmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="92b46-156">Updates the shared access signature (SAS) token value for storage credentials created with a shared access signature.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>