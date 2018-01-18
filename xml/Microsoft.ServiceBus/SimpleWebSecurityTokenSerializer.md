<Type Name="SimpleWebSecurityTokenSerializer" FullName="Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer">
  <TypeSignature Language="C#" Value="public class SimpleWebSecurityTokenSerializer : System.IdentityModel.Selectors.SecurityTokenSerializer" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SimpleWebSecurityTokenSerializer extends System.IdentityModel.Selectors.SecurityTokenSerializer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer" />
  <TypeSignature Language="VB.NET" Value="Public Class SimpleWebSecurityTokenSerializer&#xA;Inherits SecurityTokenSerializer" />
  <TypeSignature Language="F#" Value="type SimpleWebSecurityTokenSerializer = class&#xA;    inherit SecurityTokenSerializer" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.IdentityModel.Selectors.SecurityTokenSerializer</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="49128-101">Stellt eine Klasse, die zum Lesen und Schreiben verwendet <see cref="T:Microsoft.ServiceBus.SimpleWebSecurityToken" />, <see cref="T:System.IdentityModel.Tokens.SecurityKeyIdentifierClause" />, und <see cref="T:System.IdentityModel.Tokens.SecurityKeyIdentifier" /> Objekte als XML.</span><span class="sxs-lookup"><span data-stu-id="49128-101">Represents a class to use to read and to write <see cref="T:Microsoft.ServiceBus.SimpleWebSecurityToken" />, <see cref="T:System.IdentityModel.Tokens.SecurityKeyIdentifierClause" />, and <see cref="T:System.IdentityModel.Tokens.SecurityKeyIdentifier" /> objects as XML.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SimpleWebSecurityTokenSerializer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="49128-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="49128-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SimpleWebSecurityTokenSerializer (System.IdentityModel.Selectors.SecurityTokenSerializer innerSerializer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.IdentityModel.Selectors.SecurityTokenSerializer innerSerializer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer.#ctor(System.IdentityModel.Selectors.SecurityTokenSerializer)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (innerSerializer As SecurityTokenSerializer)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer : System.IdentityModel.Selectors.SecurityTokenSerializer -&gt; Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer" Usage="new Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer innerSerializer" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="innerSerializer" Type="System.IdentityModel.Selectors.SecurityTokenSerializer" />
      </Parameters>
      <Docs>
        <param name="innerSerializer"><span data-ttu-id="49128-103">Einen SecurityTokenSerializer, um umbrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="49128-103">A SecurityTokenSerializer to wrap.</span></span> <span data-ttu-id="49128-104">In der Regel das Standardserialisierungsprogramm WCF</span><span class="sxs-lookup"><span data-stu-id="49128-104">Typically the default WCF serializer</span></span></param>
        <summary>
            <span data-ttu-id="49128-105">Konstruktor.</span><span class="sxs-lookup"><span data-stu-id="49128-105">Constructor.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanReadKeyIdentifierClauseCore">
      <MemberSignature Language="C#" Value="protected override bool CanReadKeyIdentifierClauseCore (System.Xml.XmlReader reader);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool CanReadKeyIdentifierClauseCore(class System.Xml.XmlReader reader) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer.CanReadKeyIdentifierClauseCore(System.Xml.XmlReader)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CanReadKeyIdentifierClauseCore (reader As XmlReader) As Boolean" />
      <MemberSignature Language="F#" Value="override this.CanReadKeyIdentifierClauseCore : System.Xml.XmlReader -&gt; bool" Usage="simpleWebSecurityTokenSerializer.CanReadKeyIdentifierClauseCore reader" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="System.Xml.XmlReader" />
      </Parameters>
      <Docs>
        <param name="reader"><span data-ttu-id="49128-106">Ein <see cref="T:System.Xml.XmlReader" />, um die Schlüsselbezeichnerklausel zu lesen.</span><span class="sxs-lookup"><span data-stu-id="49128-106">An <see cref="T:System.Xml.XmlReader" /> to read the key identifier clause.</span></span></param>
        <summary><span data-ttu-id="49128-107">Bestimmt, ob dieses Serialisierungsprogramm lesen kann die &lt;KeyIdentifier&gt; Element durch den angegebenen XML-Reader verwiesen wird.</span><span class="sxs-lookup"><span data-stu-id="49128-107">Determines whether this serializer can read the &lt;KeyIdentifier&gt; element referred  by the specified XML reader.</span></span></summary>
        <returns><span data-ttu-id="49128-108">True, wenn das angegebene &lt;KeyIdentifier&gt; Element kann gelesen werden soll, andernfalls "false" sein.</span><span class="sxs-lookup"><span data-stu-id="49128-108">true when the specified &lt;KeyIdentifier&gt; element can be read; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanReadKeyIdentifierCore">
      <MemberSignature Language="C#" Value="protected override bool CanReadKeyIdentifierCore (System.Xml.XmlReader reader);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool CanReadKeyIdentifierCore(class System.Xml.XmlReader reader) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer.CanReadKeyIdentifierCore(System.Xml.XmlReader)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CanReadKeyIdentifierCore (reader As XmlReader) As Boolean" />
      <MemberSignature Language="F#" Value="override this.CanReadKeyIdentifierCore : System.Xml.XmlReader -&gt; bool" Usage="simpleWebSecurityTokenSerializer.CanReadKeyIdentifierCore reader" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="System.Xml.XmlReader" />
      </Parameters>
      <Docs>
        <param name="reader"><span data-ttu-id="49128-109">Ein <see cref="T:System.Xml.XmlReader" />, um den Schlüsselbezeichner zu lesen.</span><span class="sxs-lookup"><span data-stu-id="49128-109">An <see cref="T:System.Xml.XmlReader" /> to read the key identifier.</span></span></param>
        <summary><span data-ttu-id="49128-110">Bestimmt, ob dieses Serialisierungsprogramm lesen kann die &lt;KeyIdentifier&gt; Element durch den angegebenen XML-Reader verwiesen wird.</span><span class="sxs-lookup"><span data-stu-id="49128-110">Determines whether this serializer can read the &lt;KeyIdentifier&gt; element referred  by the specified XML reader.</span></span></summary>
        <returns><span data-ttu-id="49128-111">True, wenn das angegebene &lt;KeyIdentifier&gt; Element kann gelesen werden soll, andernfalls "false" sein.</span><span class="sxs-lookup"><span data-stu-id="49128-111">true when the specified &lt;KeyIdentifier&gt; element can be read; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanReadTokenCore">
      <MemberSignature Language="C#" Value="protected override bool CanReadTokenCore (System.Xml.XmlReader reader);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool CanReadTokenCore(class System.Xml.XmlReader reader) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer.CanReadTokenCore(System.Xml.XmlReader)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CanReadTokenCore (reader As XmlReader) As Boolean" />
      <MemberSignature Language="F#" Value="override this.CanReadTokenCore : System.Xml.XmlReader -&gt; bool" Usage="simpleWebSecurityTokenSerializer.CanReadTokenCore reader" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="System.Xml.XmlReader" />
      </Parameters>
      <Docs>
        <param name="reader"><span data-ttu-id="49128-112">Ein <see cref="T:System.Xml.XmlReader" /> zum Lesen des Sicherheitstokens.</span><span class="sxs-lookup"><span data-stu-id="49128-112">An <see cref="T:System.Xml.XmlReader" /> to read the security token.</span></span></param>
        <summary><span data-ttu-id="49128-113">Bestimmt, ob dieses Serialisierungsprogramm das Sicherheitstoken lesen kann, auf das der angegebene XML-Reader zeigt.</span><span class="sxs-lookup"><span data-stu-id="49128-113">Determines whether this serializer can read the security token pointed at by the specified XML reader.</span></span></summary>
        <returns><span data-ttu-id="49128-114">"true", wenn das Sicherheitstoken gelesen werden kann; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="49128-114">true when the security token can be read; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanWriteKeyIdentifierClauseCore">
      <MemberSignature Language="C#" Value="protected override bool CanWriteKeyIdentifierClauseCore (System.IdentityModel.Tokens.SecurityKeyIdentifierClause keyIdentifierClause);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool CanWriteKeyIdentifierClauseCore(class System.IdentityModel.Tokens.SecurityKeyIdentifierClause keyIdentifierClause) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer.CanWriteKeyIdentifierClauseCore(System.IdentityModel.Tokens.SecurityKeyIdentifierClause)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CanWriteKeyIdentifierClauseCore (keyIdentifierClause As SecurityKeyIdentifierClause) As Boolean" />
      <MemberSignature Language="F#" Value="override this.CanWriteKeyIdentifierClauseCore : System.IdentityModel.Tokens.SecurityKeyIdentifierClause -&gt; bool" Usage="simpleWebSecurityTokenSerializer.CanWriteKeyIdentifierClauseCore keyIdentifierClause" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyIdentifierClause" Type="System.IdentityModel.Tokens.SecurityKeyIdentifierClause" />
      </Parameters>
      <Docs>
        <param name="keyIdentifierClause"> <span data-ttu-id="49128-115">Eine <see cref="T:System.IdentityModel.Tokens.SecurityKeyIdentifierClause" />, die die Schlüsselbezeichnerklausel darstellt, die geschrieben werden soll.</span><span class="sxs-lookup"><span data-stu-id="49128-115">A <see cref="T:System.IdentityModel.Tokens.SecurityKeyIdentifierClause" /> that represents the key identifier clause to write.</span></span></param>
        <summary><span data-ttu-id="49128-116">Bestimmt, ob dieses Serialisierungsprogramm die angegebene Schlüsselbezeichnerklausel schreiben kann.</span><span class="sxs-lookup"><span data-stu-id="49128-116">Determines whether this serializer can write the specified key identifier clause.</span></span></summary>
        <returns><span data-ttu-id="49128-117">"true", wenn dieses Serialisierungsprogramm die angegebene schlüsselbezeichnerklausel schreiben kann; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="49128-117">true when this serializer can write the specified key identifier clause; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanWriteKeyIdentifierCore">
      <MemberSignature Language="C#" Value="protected override bool CanWriteKeyIdentifierCore (System.IdentityModel.Tokens.SecurityKeyIdentifier keyIdentifier);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool CanWriteKeyIdentifierCore(class System.IdentityModel.Tokens.SecurityKeyIdentifier keyIdentifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer.CanWriteKeyIdentifierCore(System.IdentityModel.Tokens.SecurityKeyIdentifier)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CanWriteKeyIdentifierCore (keyIdentifier As SecurityKeyIdentifier) As Boolean" />
      <MemberSignature Language="F#" Value="override this.CanWriteKeyIdentifierCore : System.IdentityModel.Tokens.SecurityKeyIdentifier -&gt; bool" Usage="simpleWebSecurityTokenSerializer.CanWriteKeyIdentifierCore keyIdentifier" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyIdentifier" Type="System.IdentityModel.Tokens.SecurityKeyIdentifier" />
      </Parameters>
      <Docs>
        <param name="keyIdentifier"> <span data-ttu-id="49128-118">Ein <see cref="T:System.IdentityModel.Tokens.SecurityKeyIdentifier" />, der den Schlüsselbezeichner darstellt, der geschrieben werden soll.</span><span class="sxs-lookup"><span data-stu-id="49128-118">A <see cref="T:System.IdentityModel.Tokens.SecurityKeyIdentifier" /> that represents the key identifier to write.</span></span></param>
        <summary><span data-ttu-id="49128-119">Bestimmt, ob dieses Serialisierungsprogramm den angegebenen Schlüsselbezeichner schreiben kann.</span><span class="sxs-lookup"><span data-stu-id="49128-119">Determines whether this serializer can write the specified key identifier.</span></span></summary>
        <returns><span data-ttu-id="49128-120">"true", wenn dieses Serialisierungsprogramm den angegebenen Schlüsselbezeichner schreiben kann; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="49128-120">true when this serializer can write the specified key identifier; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanWriteTokenCore">
      <MemberSignature Language="C#" Value="protected override bool CanWriteTokenCore (System.IdentityModel.Tokens.SecurityToken token);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool CanWriteTokenCore(class System.IdentityModel.Tokens.SecurityToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer.CanWriteTokenCore(System.IdentityModel.Tokens.SecurityToken)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CanWriteTokenCore (token As SecurityToken) As Boolean" />
      <MemberSignature Language="F#" Value="override this.CanWriteTokenCore : System.IdentityModel.Tokens.SecurityToken -&gt; bool" Usage="simpleWebSecurityTokenSerializer.CanWriteTokenCore token" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="System.IdentityModel.Tokens.SecurityToken" />
      </Parameters>
      <Docs>
        <param name="token"> <span data-ttu-id="49128-121">Das <see cref="T:System.IdentityModel.Tokens.SecurityToken" />-Sicherheitstoken, das in XML konvertiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="49128-121">The <see cref="T:System.IdentityModel.Tokens.SecurityToken" /> to convert to XML.</span></span></param>
        <summary><span data-ttu-id="49128-122">Bestimmt, ob dieses Serialisierungsprogramm das angegebene Sicherheitstoken in XML schreiben kann.</span><span class="sxs-lookup"><span data-stu-id="49128-122">Determines whether this serializer can write the specified security token to XML.</span></span></summary>
        <returns><span data-ttu-id="49128-123">"true", wenn das Sicherheitstoken geschrieben werden kann; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="49128-123">true when the security token can be written; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultInstance">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer DefaultInstance;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer DefaultInstance" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer.DefaultInstance" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly DefaultInstance As SimpleWebSecurityTokenSerializer " />
      <MemberSignature Language="F#" Value=" staticval mutable DefaultInstance : Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer" Usage="Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer.DefaultInstance" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="49128-124">Gibt eine Instanz der<see cref="T:Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer" /> Klasse.</span><span class="sxs-lookup"><span data-stu-id="49128-124">Specifies an instance of the<see cref="T:Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadKeyIdentifierClauseCore">
      <MemberSignature Language="C#" Value="protected override System.IdentityModel.Tokens.SecurityKeyIdentifierClause ReadKeyIdentifierClauseCore (System.Xml.XmlReader reader);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IdentityModel.Tokens.SecurityKeyIdentifierClause ReadKeyIdentifierClauseCore(class System.Xml.XmlReader reader) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer.ReadKeyIdentifierClauseCore(System.Xml.XmlReader)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function ReadKeyIdentifierClauseCore (reader As XmlReader) As SecurityKeyIdentifierClause" />
      <MemberSignature Language="F#" Value="override this.ReadKeyIdentifierClauseCore : System.Xml.XmlReader -&gt; System.IdentityModel.Tokens.SecurityKeyIdentifierClause" Usage="simpleWebSecurityTokenSerializer.ReadKeyIdentifierClauseCore reader" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IdentityModel.Tokens.SecurityKeyIdentifierClause</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="System.Xml.XmlReader" />
      </Parameters>
      <Docs>
        <param name="reader"><span data-ttu-id="49128-125">Ein <see cref="T:System.Xml.XmlReader" />, um die Schlüsselbezeichnerklausel zu lesen.</span><span class="sxs-lookup"><span data-stu-id="49128-125">An <see cref="T:System.Xml.XmlReader" /> to read the key identifier clause.</span></span></param>
        <summary><span data-ttu-id="49128-126">Liest die schlüsselbezeichnerklausel mit dem angegebenen XML-Reader.</span><span class="sxs-lookup"><span data-stu-id="49128-126">Reads the key identifier clause using the specified XML reader.</span></span></summary>
        <returns><span data-ttu-id="49128-127">Ein <see cref="T:System.IdentityModel.Tokens.SecurityKeyIdentifierClause" />, der den Schlüsselbezeichner darstellt, der gelesen wird.</span><span class="sxs-lookup"><span data-stu-id="49128-127">A <see cref="T:System.IdentityModel.Tokens.SecurityKeyIdentifierClause" /> that represents the key identifier that is read.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadKeyIdentifierCore">
      <MemberSignature Language="C#" Value="protected override System.IdentityModel.Tokens.SecurityKeyIdentifier ReadKeyIdentifierCore (System.Xml.XmlReader reader);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IdentityModel.Tokens.SecurityKeyIdentifier ReadKeyIdentifierCore(class System.Xml.XmlReader reader) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer.ReadKeyIdentifierCore(System.Xml.XmlReader)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function ReadKeyIdentifierCore (reader As XmlReader) As SecurityKeyIdentifier" />
      <MemberSignature Language="F#" Value="override this.ReadKeyIdentifierCore : System.Xml.XmlReader -&gt; System.IdentityModel.Tokens.SecurityKeyIdentifier" Usage="simpleWebSecurityTokenSerializer.ReadKeyIdentifierCore reader" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IdentityModel.Tokens.SecurityKeyIdentifier</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="System.Xml.XmlReader" />
      </Parameters>
      <Docs>
        <param name="reader"><span data-ttu-id="49128-128">Ein <see cref="T:System.Xml.XmlReader" />, um den Schlüsselbezeichner zu lesen.</span><span class="sxs-lookup"><span data-stu-id="49128-128">An <see cref="T:System.Xml.XmlReader" /> to read the key identifier.</span></span></param>
        <summary><span data-ttu-id="49128-129">Liest den Schlüsselbezeichner mit dem angegebenen XML-Reader.</span><span class="sxs-lookup"><span data-stu-id="49128-129">Reads the key identifier using the specified XML reader.</span></span></summary>
        <returns><span data-ttu-id="49128-130">Ein <see cref="T:System.IdentityModel.Tokens.SecurityKeyIdentifier" />, der den Schlüsselbezeichner darstellt, der gelesen wird.</span><span class="sxs-lookup"><span data-stu-id="49128-130">A <see cref="T:System.IdentityModel.Tokens.SecurityKeyIdentifier" /> that represents the key identifier that is read.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadTokenCore">
      <MemberSignature Language="C#" Value="protected override System.IdentityModel.Tokens.SecurityToken ReadTokenCore (System.Xml.XmlReader reader, System.IdentityModel.Selectors.SecurityTokenResolver tokenResolver);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IdentityModel.Tokens.SecurityToken ReadTokenCore(class System.Xml.XmlReader reader, class System.IdentityModel.Selectors.SecurityTokenResolver tokenResolver) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer.ReadTokenCore(System.Xml.XmlReader,System.IdentityModel.Selectors.SecurityTokenResolver)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function ReadTokenCore (reader As XmlReader, tokenResolver As SecurityTokenResolver) As SecurityToken" />
      <MemberSignature Language="F#" Value="override this.ReadTokenCore : System.Xml.XmlReader * System.IdentityModel.Selectors.SecurityTokenResolver -&gt; System.IdentityModel.Tokens.SecurityToken" Usage="simpleWebSecurityTokenSerializer.ReadTokenCore (reader, tokenResolver)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IdentityModel.Tokens.SecurityToken</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="System.Xml.XmlReader" />
        <Parameter Name="tokenResolver" Type="System.IdentityModel.Selectors.SecurityTokenResolver" />
      </Parameters>
      <Docs>
        <param name="reader"> <span data-ttu-id="49128-131">Ein <see cref="T:System.Xml.XmlReader" /> zum Lesen der SimpleWebSecurityToken oder das Sicherheitstoken.</span><span class="sxs-lookup"><span data-stu-id="49128-131">An <see cref="T:System.Xml.XmlReader" /> to read the SimpleWebSecurityToken or the security token.</span></span></param>
        <param name="tokenResolver"> <span data-ttu-id="49128-132">Ein <see cref="T:System.IdentityModel.Selectors.SecurityTokenResolver" />, der den Typ des Sicherheitstokens bestimmt.</span><span class="sxs-lookup"><span data-stu-id="49128-132">A <see cref="T:System.IdentityModel.Selectors.SecurityTokenResolver" /> that determines the security token type.</span></span></param>
        <summary><span data-ttu-id="49128-133">Liest die<see cref="T:Microsoft.ServiceBus.SimpleWebSecurityToken" /> oder das Sicherheitstoken, die an die angegebene XML-Reader zeigt.</span><span class="sxs-lookup"><span data-stu-id="49128-133">Reads the<see cref="T:Microsoft.ServiceBus.SimpleWebSecurityToken" /> or the security token pointed at by the specified XML reader.</span></span></summary>
        <returns><span data-ttu-id="49128-134">Ein<see cref="T:System.IdentityModel.Tokens.SecurityToken" /> , darstellt, die SimpleWebSecurityToken oder das Sicherheitstoken, das gelesen wird.</span><span class="sxs-lookup"><span data-stu-id="49128-134">A<see cref="T:System.IdentityModel.Tokens.SecurityToken" /> that represents the SimpleWebSecurityToken or the security token that is read.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.NotSupportedException"> <span data-ttu-id="49128-135">Die Codierung des XML-Elements ist nicht base64Binary.</span><span class="sxs-lookup"><span data-stu-id="49128-135">The encoding of the XML element is not base64Binary.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="WriteKeyIdentifierClauseCore">
      <MemberSignature Language="C#" Value="protected override void WriteKeyIdentifierClauseCore (System.Xml.XmlWriter writer, System.IdentityModel.Tokens.SecurityKeyIdentifierClause keyIdentifierClause);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void WriteKeyIdentifierClauseCore(class System.Xml.XmlWriter writer, class System.IdentityModel.Tokens.SecurityKeyIdentifierClause keyIdentifierClause) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer.WriteKeyIdentifierClauseCore(System.Xml.XmlWriter,System.IdentityModel.Tokens.SecurityKeyIdentifierClause)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub WriteKeyIdentifierClauseCore (writer As XmlWriter, keyIdentifierClause As SecurityKeyIdentifierClause)" />
      <MemberSignature Language="F#" Value="override this.WriteKeyIdentifierClauseCore : System.Xml.XmlWriter * System.IdentityModel.Tokens.SecurityKeyIdentifierClause -&gt; unit" Usage="simpleWebSecurityTokenSerializer.WriteKeyIdentifierClauseCore (writer, keyIdentifierClause)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="writer" Type="System.Xml.XmlWriter" />
        <Parameter Name="keyIdentifierClause" Type="System.IdentityModel.Tokens.SecurityKeyIdentifierClause" />
      </Parameters>
      <Docs>
        <param name="writer"> <span data-ttu-id="49128-136">Ein <see cref="T:System.Xml.XmlWriter" /> verwendet, um die dazugehörige schlüsselbezeichnerklausel zu schreiben.</span><span class="sxs-lookup"><span data-stu-id="49128-136">An <see cref="T:System.Xml.XmlWriter" /> used to write the key identifier clause.</span></span></param>
        <param name="keyIdentifierClause"> <span data-ttu-id="49128-137">Eine <see cref="T:System.IdentityModel.Tokens.SecurityKeyIdentifierClause" />, die die Schlüsselbezeichnerklausel darstellt, die geschrieben werden soll.</span><span class="sxs-lookup"><span data-stu-id="49128-137">A <see cref="T:System.IdentityModel.Tokens.SecurityKeyIdentifierClause" /> that represents the key identifier clause to write.</span></span></param>
        <summary><span data-ttu-id="49128-138">Schreibt die angegebene Schlüsselbezeichnerklausel mit dem angegebenen XML-Writer.</span><span class="sxs-lookup"><span data-stu-id="49128-138">Writes the specified key identifier clause using the specified XML writer.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteKeyIdentifierCore">
      <MemberSignature Language="C#" Value="protected override void WriteKeyIdentifierCore (System.Xml.XmlWriter writer, System.IdentityModel.Tokens.SecurityKeyIdentifier keyIdentifier);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void WriteKeyIdentifierCore(class System.Xml.XmlWriter writer, class System.IdentityModel.Tokens.SecurityKeyIdentifier keyIdentifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer.WriteKeyIdentifierCore(System.Xml.XmlWriter,System.IdentityModel.Tokens.SecurityKeyIdentifier)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub WriteKeyIdentifierCore (writer As XmlWriter, keyIdentifier As SecurityKeyIdentifier)" />
      <MemberSignature Language="F#" Value="override this.WriteKeyIdentifierCore : System.Xml.XmlWriter * System.IdentityModel.Tokens.SecurityKeyIdentifier -&gt; unit" Usage="simpleWebSecurityTokenSerializer.WriteKeyIdentifierCore (writer, keyIdentifier)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="writer" Type="System.Xml.XmlWriter" />
        <Parameter Name="keyIdentifier" Type="System.IdentityModel.Tokens.SecurityKeyIdentifier" />
      </Parameters>
      <Docs>
        <param name="writer"> <span data-ttu-id="49128-139">Ein <see cref="T:System.Xml.XmlWriter" /> verwendet, um den Schlüsselbezeichner schreiben.</span><span class="sxs-lookup"><span data-stu-id="49128-139">An <see cref="T:System.Xml.XmlWriter" /> used to write the key identifier.</span></span></param>
        <param name="keyIdentifier"> <span data-ttu-id="49128-140">Ein <see cref="T:System.IdentityModel.Tokens.SecurityKeyIdentifier" />, der den Schlüsselbezeichner darstellt, der geschrieben werden soll.</span><span class="sxs-lookup"><span data-stu-id="49128-140">A <see cref="T:System.IdentityModel.Tokens.SecurityKeyIdentifier" /> that represents the key identifier to write.</span></span></param>
        <summary><span data-ttu-id="49128-141">Schreibt den angegebenen Schlüsselbezeichner mit dem angegebenen XML-Writer.</span><span class="sxs-lookup"><span data-stu-id="49128-141">Writes the specified key identifier using the specified XML writer.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.InvalidOperationException"> <span data-ttu-id="49128-142">Der Inhalt im Binärformat token ist null.</span><span class="sxs-lookup"><span data-stu-id="49128-142">The binary token content is null.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="WriteTokenCore">
      <MemberSignature Language="C#" Value="protected override void WriteTokenCore (System.Xml.XmlWriter writer, System.IdentityModel.Tokens.SecurityToken token);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void WriteTokenCore(class System.Xml.XmlWriter writer, class System.IdentityModel.Tokens.SecurityToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer.WriteTokenCore(System.Xml.XmlWriter,System.IdentityModel.Tokens.SecurityToken)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub WriteTokenCore (writer As XmlWriter, token As SecurityToken)" />
      <MemberSignature Language="F#" Value="override this.WriteTokenCore : System.Xml.XmlWriter * System.IdentityModel.Tokens.SecurityToken -&gt; unit" Usage="simpleWebSecurityTokenSerializer.WriteTokenCore (writer, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="writer" Type="System.Xml.XmlWriter" />
        <Parameter Name="token" Type="System.IdentityModel.Tokens.SecurityToken" />
      </Parameters>
      <Docs>
        <param name="writer"> <span data-ttu-id="49128-143">Ein <see cref="T:System.Xml.XmlWriter" /> verwendet, um das Schreiben des SimpleWebSecurityToken oder Sicherheit token.</span><span class="sxs-lookup"><span data-stu-id="49128-143">An <see cref="T:System.Xml.XmlWriter" /> used to write the SimpleWebSecurityToken or security token.</span></span></param>
        <param name="token"> <span data-ttu-id="49128-144">Der SimpleWebSecurityToken oder Sicherheit token um zu schreiben.</span><span class="sxs-lookup"><span data-stu-id="49128-144">The SimpleWebSecurityToken or security token to write.</span></span></param>
        <summary><span data-ttu-id="49128-145">Schreibt das angegebene<see cref="T:Microsoft.ServiceBus.SimpleWebSecurityToken" /> oder Sicherheitstoken, die mit dem angegebenen XML-Writer.</span><span class="sxs-lookup"><span data-stu-id="49128-145">Writes the specified<see cref="T:Microsoft.ServiceBus.SimpleWebSecurityToken" /> or security token using the specified XML writer.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>