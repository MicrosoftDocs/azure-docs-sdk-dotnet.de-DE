<Type Name="EncryptionUtility" FullName="System.Fabric.Security.EncryptionUtility">
  <TypeSignature Language="C#" Value="public sealed class EncryptionUtility" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit EncryptionUtility extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Security.EncryptionUtility" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class EncryptionUtility" />
  <TypeSignature Language="F#" Value="type EncryptionUtility = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="40a9a-101">Stellt die Encryption-Hilfsprogramm dar.</span><span class="sxs-lookup"><span data-stu-id="40a9a-101">Represents the encryption utility.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EncryptionUtility ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Security.EncryptionUtility.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="40a9a-102">Instanziiert eine neue <see cref="T:System.Fabric.Security.EncryptionUtility" /> Klasse.</span><span class="sxs-lookup"><span data-stu-id="40a9a-102">Instantiates a new <see cref="T:System.Fabric.Security.EncryptionUtility" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DecryptText">
      <MemberSignature Language="C#" Value="public static System.Security.SecureString DecryptText (string textToDecrypt);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Security.SecureString DecryptText(string textToDecrypt) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Security.EncryptionUtility.DecryptText(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function DecryptText (textToDecrypt As String) As SecureString" />
      <MemberSignature Language="F#" Value="static member DecryptText : string -&gt; System.Security.SecureString" Usage="System.Fabric.Security.EncryptionUtility.DecryptText textToDecrypt" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Security.SecureString</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="textToDecrypt" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="textToDecrypt">
          <para><span data-ttu-id="40a9a-103">Der verschlüsselte Text entschlüsselt.</span><span class="sxs-lookup"><span data-stu-id="40a9a-103">The encrypted text to decrypt.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="40a9a-104">Entschlüsseln Sie eine Textzeichenfolge, die von Methoden EncryptText verschlüsselt <see cref="T:System.Fabric.Security.EncryptionUtility" />, es wird davon ausgegangen, dass der Speicherort des Entschlüsselungszertifikats LocalMachine ist.</span><span class="sxs-lookup"><span data-stu-id="40a9a-104">Decrypt a text string encrypted by EncryptText methods of <see cref="T:System.Fabric.Security.EncryptionUtility" />, it is assumed that the store location of decryption certificate is LocalMachine.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="40a9a-105">Der verschlüsselte Text als <see cref="T:System.Security.SecureString" />.</span><span class="sxs-lookup"><span data-stu-id="40a9a-105">The decrypted text as <see cref="T:System.Security.SecureString" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DecryptText">
      <MemberSignature Language="C#" Value="public static System.Security.SecureString DecryptText (string textToDecrypt, System.Security.Cryptography.X509Certificates.StoreLocation storeLocation);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Security.SecureString DecryptText(string textToDecrypt, valuetype System.Security.Cryptography.X509Certificates.StoreLocation storeLocation) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Security.EncryptionUtility.DecryptText(System.String,System.Security.Cryptography.X509Certificates.StoreLocation)" />
      <MemberSignature Language="F#" Value="static member DecryptText : string * System.Security.Cryptography.X509Certificates.StoreLocation -&gt; System.Security.SecureString" Usage="System.Fabric.Security.EncryptionUtility.DecryptText (textToDecrypt, storeLocation)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Security.SecureString</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="textToDecrypt" Type="System.String" />
        <Parameter Name="storeLocation" Type="System.Security.Cryptography.X509Certificates.StoreLocation" />
      </Parameters>
      <Docs>
        <param name="textToDecrypt">
          <para><span data-ttu-id="40a9a-106">Der verschlüsselte Text entschlüsselt.</span><span class="sxs-lookup"><span data-stu-id="40a9a-106">The encrypted text to decrypt.</span></span></para>
        </param>
        <param name="storeLocation">
          <para><span data-ttu-id="40a9a-107">Das Zertifikat-Speicherort Entschlüsselungszertifikat abgerufen.</span><span class="sxs-lookup"><span data-stu-id="40a9a-107">The certificate store location to retrieve decryption certificate.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="40a9a-108">Entschlüsseln Sie eine Textzeichenfolge, die von Methoden EncryptText verschlüsselt <see cref="T:System.Fabric.Security.EncryptionUtility" />.</span><span class="sxs-lookup"><span data-stu-id="40a9a-108">Decrypt a text string encrypted by EncryptText methods of <see cref="T:System.Fabric.Security.EncryptionUtility" />.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="40a9a-109">Der verschlüsselte Text als <see cref="T:System.Security.SecureString" />.</span><span class="sxs-lookup"><span data-stu-id="40a9a-109">The decrypted text as <see cref="T:System.Security.SecureString" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DecryptValue">
      <MemberSignature Language="C#" Value="public static string DecryptValue (string textToDecrypt);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string DecryptValue(string textToDecrypt) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Security.EncryptionUtility.DecryptValue(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function DecryptValue (textToDecrypt As String) As String" />
      <MemberSignature Language="F#" Value="static member DecryptValue : string -&gt; string" Usage="System.Fabric.Security.EncryptionUtility.DecryptValue textToDecrypt" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Deprecated DecryptText", false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="textToDecrypt" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="textToDecrypt">
          <para><span data-ttu-id="40a9a-110">Der Zeichenfolgenwert zu entschlüsseln.</span><span class="sxs-lookup"><span data-stu-id="40a9a-110">The string value to decrypt.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="40a9a-111">Entschlüsselt die Zeichenfolgenwerte, die durch Aufrufen von EncryptValue verschlüsselt wurden.</span><span class="sxs-lookup"><span data-stu-id="40a9a-111">Decrypts string values that were encrypted by calling EncryptValue.</span></span> <span data-ttu-id="40a9a-112">Diese Methode ist veraltet. EncryptText-Methode sollte stattdessen verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="40a9a-112">This method is deprecated; EncryptText method should be used instead.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="40a9a-113">Der entschlüsselte Wert.</span><span class="sxs-lookup"><span data-stu-id="40a9a-113">The decrypted value.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptText">
      <MemberSignature Language="C#" Value="public static string EncryptText (string textToEncrypt, string thumbprint, string storeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string EncryptText(string textToEncrypt, string thumbprint, string storeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Security.EncryptionUtility.EncryptText(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function EncryptText (textToEncrypt As String, thumbprint As String, storeName As String) As String" />
      <MemberSignature Language="F#" Value="static member EncryptText : string * string * string -&gt; string" Usage="System.Fabric.Security.EncryptionUtility.EncryptText (textToEncrypt, thumbprint, storeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="textToEncrypt" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="storeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="textToEncrypt">
          <para><span data-ttu-id="40a9a-114">Die Textzeichenfolge zu verschlüsseln.</span><span class="sxs-lookup"><span data-stu-id="40a9a-114">The text string to encrypt.</span></span></para>
        </param>
        <param name="thumbprint">
          <para><span data-ttu-id="40a9a-115">Der Fingerabdruck des Verschlüsselungszertifikats.</span><span class="sxs-lookup"><span data-stu-id="40a9a-115">The thumbprint of encryption certificate.</span></span></para>
        </param>
        <param name="storeName">
          <para><span data-ttu-id="40a9a-116">Der Name des Zertifikatspeichers, aus denen Verschlüsselungsschlüssel Zertifikat abgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="40a9a-116">The name of certificate store, from which encryption certificate is retrieved.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="40a9a-117">Verschlüsseln der Zeichenfolge mit einem installierten X509 Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="40a9a-117">Encrypt text string with an installed X509 certificate.</span></span> <span data-ttu-id="40a9a-118">Zertifikatspeicherort LocalMachine und der Verschlüsselungsalgorithmus AES256 CBC.</span><span class="sxs-lookup"><span data-stu-id="40a9a-118">Certificate store location is LocalMachine and the encryption algorithm is AES256 CBC.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="40a9a-119">Der verschlüsselte Text als <see cref="T:System.String" />.</span><span class="sxs-lookup"><span data-stu-id="40a9a-119">The encrypted text as <see cref="T:System.String" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptText">
      <MemberSignature Language="C#" Value="public static string EncryptText (string textToEncrypt, string thumbprint, string storeName, System.Security.Cryptography.X509Certificates.StoreLocation storeLocation, string algorithmOid);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string EncryptText(string textToEncrypt, string thumbprint, string storeName, valuetype System.Security.Cryptography.X509Certificates.StoreLocation storeLocation, string algorithmOid) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Security.EncryptionUtility.EncryptText(System.String,System.String,System.String,System.Security.Cryptography.X509Certificates.StoreLocation,System.String)" />
      <MemberSignature Language="F#" Value="static member EncryptText : string * string * string * System.Security.Cryptography.X509Certificates.StoreLocation * string -&gt; string" Usage="System.Fabric.Security.EncryptionUtility.EncryptText (textToEncrypt, thumbprint, storeName, storeLocation, algorithmOid)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="textToEncrypt" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="storeName" Type="System.String" />
        <Parameter Name="storeLocation" Type="System.Security.Cryptography.X509Certificates.StoreLocation" />
        <Parameter Name="algorithmOid" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="textToEncrypt">
          <para><span data-ttu-id="40a9a-120">Der Text verschlüsselt.</span><span class="sxs-lookup"><span data-stu-id="40a9a-120">The text to encrypt.</span></span></para>
        </param>
        <param name="thumbprint">
          <para><span data-ttu-id="40a9a-121">Der Fingerabdruck des Verschlüsselungszertifikats.</span><span class="sxs-lookup"><span data-stu-id="40a9a-121">The thumbprint of encryption certificate.</span></span></para>
        </param>
        <param name="storeName">
          <para><span data-ttu-id="40a9a-122">Der Name des Zertifikatspeichers, aus denen Verschlüsselungsschlüssel Zertifikat abgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="40a9a-122">The name of certificate store, from which encryption certificate is retrieved.</span></span></para>
        </param>
        <param name="storeLocation">
          <para><span data-ttu-id="40a9a-123">Der Zertifikatsspeicher Speicherort zum Abrufen des Verschlüsselungszertifikats.</span><span class="sxs-lookup"><span data-stu-id="40a9a-123">The certificate store location to retrieve encryption certificate.</span></span></para>
        </param>
        <param name="algorithmOid">
          <para><span data-ttu-id="40a9a-124">Die Verschlüsselung Algorithmus Objekt-ID (OID).</span><span class="sxs-lookup"><span data-stu-id="40a9a-124">The encryption algorithm object identifier (OID).</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="40a9a-125">Verschlüsseln der Zeichenfolge mit einem installierten X509 Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="40a9a-125">Encrypt text string with an installed X509 certificate.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="40a9a-126">Der verschlüsselte Text als <see cref="T:System.String" />.</span><span class="sxs-lookup"><span data-stu-id="40a9a-126">The encrypted text as <see cref="T:System.String" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptTextByCertFile">
      <MemberSignature Language="C#" Value="public static string EncryptTextByCertFile (string textToEncrypt, string certFileName, string algorithmOid);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string EncryptTextByCertFile(string textToEncrypt, string certFileName, string algorithmOid) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Security.EncryptionUtility.EncryptTextByCertFile(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function EncryptTextByCertFile (textToEncrypt As String, certFileName As String, algorithmOid As String) As String" />
      <MemberSignature Language="F#" Value="static member EncryptTextByCertFile : string * string * string -&gt; string" Usage="System.Fabric.Security.EncryptionUtility.EncryptTextByCertFile (textToEncrypt, certFileName, algorithmOid)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="textToEncrypt" Type="System.String" />
        <Parameter Name="certFileName" Type="System.String" />
        <Parameter Name="algorithmOid" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="textToEncrypt">
          <para><span data-ttu-id="40a9a-127">Der Text verschlüsselt.</span><span class="sxs-lookup"><span data-stu-id="40a9a-127">The text to encrypt.</span></span></para>
        </param>
        <param name="certFileName">
          <para><span data-ttu-id="40a9a-128">Der Dateipfad der Verschlüsselung-Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="40a9a-128">The encryption certificate file path.</span></span></para>
        </param>
        <param name="algorithmOid">
          <para><span data-ttu-id="40a9a-129">Die Verschlüsselung Algorithmus Objekt-ID (OID).</span><span class="sxs-lookup"><span data-stu-id="40a9a-129">The encryption algorithm object identifier (OID).</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="40a9a-130">Verschlüsseln der Zeichenfolge mit einem X509 Zertifikat in einer Datei.</span><span class="sxs-lookup"><span data-stu-id="40a9a-130">Encrypt text string with an X509 certificate in a file.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="40a9a-131">Der verschlüsselte Text als <see cref="T:System.String" />.</span><span class="sxs-lookup"><span data-stu-id="40a9a-131">The encrypted text as <see cref="T:System.String" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptValue">
      <MemberSignature Language="C#" Value="public static string EncryptValue (string thumbprint, string storeLocation, string textToEncrypt);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string EncryptValue(string thumbprint, string storeLocation, string textToEncrypt) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Security.EncryptionUtility.EncryptValue(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function EncryptValue (thumbprint As String, storeLocation As String, textToEncrypt As String) As String" />
      <MemberSignature Language="F#" Value="static member EncryptValue : string * string * string -&gt; string" Usage="System.Fabric.Security.EncryptionUtility.EncryptValue (thumbprint, storeLocation, textToEncrypt)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Deprecated by EncryptText", false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="storeLocation" Type="System.String" />
        <Parameter Name="textToEncrypt" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="thumbprint">
          <para><span data-ttu-id="40a9a-132">Der Fingerabdruck des Zertifikats verwendet, um Text zu verschlüsseln.</span><span class="sxs-lookup"><span data-stu-id="40a9a-132">The thumbprint of certificate used to encrypt text.</span></span></para>
        </param>
        <param name="storeLocation">
          <para><span data-ttu-id="40a9a-133">Die "StoreName" für das Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="40a9a-133">The StoreName for the certificate.</span></span> <span data-ttu-id="40a9a-134">Der Standardwert ist My-Zertifikatspeicher.</span><span class="sxs-lookup"><span data-stu-id="40a9a-134">Defaults to "My" store.</span></span></para>
        </param>
        <param name="textToEncrypt">
          <para><span data-ttu-id="40a9a-135">Der Textwert, der verschlüsselt werden muss.</span><span class="sxs-lookup"><span data-stu-id="40a9a-135">The text value that needs to be encrypted.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="40a9a-136">String-Wert mit angegebenen Zertifikat verschlüsselt wird.</span><span class="sxs-lookup"><span data-stu-id="40a9a-136">Encrypts string value using specified certificate.</span></span> <span data-ttu-id="40a9a-137">Diese Methode ist veraltet. EncryptText-Methode sollte stattdessen verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="40a9a-137">This method is deprecated; EncryptText method should be used instead.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="40a9a-138">Der verschlüsselte Text als <see cref="T:System.String" />.</span><span class="sxs-lookup"><span data-stu-id="40a9a-138">The encrypted text as <see cref="T:System.String" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>