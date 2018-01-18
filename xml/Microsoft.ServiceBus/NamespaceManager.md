<Type Name="NamespaceManager" FullName="Microsoft.ServiceBus.NamespaceManager">
  <TypeSignature Language="C#" Value="public sealed class NamespaceManager" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NamespaceManager extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.NamespaceManager" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NamespaceManager" />
  <TypeSignature Language="F#" Value="type NamespaceManager = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="b9b6b-101">Stellt eine Premium-Klasse, die bei der Verwaltung von Entitäten, z. B. Warteschlangen, Themen, Abonnements und Regeln in Ihren Dienstnamespace dar.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-101">Represents an anchor class used in managing entities, such as queues, topics, subscriptions, and rules, in your service namespace.</span></span> <span data-ttu-id="b9b6b-102">Sie müssen Dienstnamespace Adresse und den Zugriff Anmeldeinformationen angeben, um Ihren Dienstnamespace zu verwalten.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-102">You must provide service namespace address and access credentials in order to manage your service namespace.</span></span></summary>
    <remarks>To be added.</remarks>
    <example>
      <code>
             <span data-ttu-id="b9b6b-103">NamespaceManagerSettings NsSettings = neue NamespaceManagerSettings(); mit den Anmeldeinformationen und Vorgang Timeout NamespaceManager-Manager neue NamespaceManager = (neue Uri("baseUri"), NsSettings);</span><span class="sxs-lookup"><span data-stu-id="b9b6b-103">NamespaceManagerSettings nsSettings = new NamespaceManagerSettings(); // with credentials and operation timeout NamespaceManager manager = new NamespaceManager(new Uri("baseUri"), nsSettings);</span></span>
             </code>
    </example>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (System.Collections.Generic.IEnumerable&lt;string&gt; addresses);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;string&gt; addresses) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.#ctor(System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (addresses As IEnumerable(Of String))" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NamespaceManager : seq&lt;string&gt; -&gt; Microsoft.ServiceBus.NamespaceManager" Usage="new Microsoft.ServiceBus.NamespaceManager addresses" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="addresses"><span data-ttu-id="b9b6b-104">Die vollständige Adressen des dienstnamespaces.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-104">The full addresses of the service namespace.</span></span></param>
        <summary><span data-ttu-id="b9b6b-105">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> Klasse mit den angegebenen Adressen.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-105">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> class with the given addresses.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (System.Collections.Generic.IEnumerable&lt;Uri&gt; addresses);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; addresses) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.#ctor(System.Collections.Generic.IEnumerable{System.Uri})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (addresses As IEnumerable(Of Uri))" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NamespaceManager : seq&lt;Uri&gt; -&gt; Microsoft.ServiceBus.NamespaceManager" Usage="new Microsoft.ServiceBus.NamespaceManager addresses" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
      </Parameters>
      <Docs>
        <param name="addresses"><span data-ttu-id="b9b6b-106">Der vollständige URI-Adressen des dienstnamespaces.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-106">The full URI addresses of the service namespace.</span></span></param>
        <summary><span data-ttu-id="b9b6b-107">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> Klasse mit den angegebenen Dienst Namespace-URI-Basisadressen.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-107">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> class with the given service namespace URI base addresses.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (string address);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (address As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NamespaceManager : string -&gt; Microsoft.ServiceBus.NamespaceManager" Usage="new Microsoft.ServiceBus.NamespaceManager address" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="b9b6b-108">Die vollständige Adresse des dienstnamespaces.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-108">The full address of the service namespace.</span></span></param>
        <summary><span data-ttu-id="b9b6b-109">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> Klasse mit dem angegebenen Namespace Dienstadresse.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-109">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> class with the given service namespace address.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (Uri address);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.#ctor(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (address As Uri)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NamespaceManager : Uri -&gt; Microsoft.ServiceBus.NamespaceManager" Usage="new Microsoft.ServiceBus.NamespaceManager address" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="b9b6b-110">Die vollständige URI-Adresse des dienstnamespaces.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-110">The full URI address of the service namespace.</span></span></param>
        <summary><span data-ttu-id="b9b6b-111">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> Klasse mit der angegebenen Service Namespace-URI-Basisadresse.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-111">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> class with the given service namespace URI base address.</span></span> </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (System.Collections.Generic.IEnumerable&lt;string&gt; addresses, Microsoft.ServiceBus.NamespaceManagerSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;string&gt; addresses, class Microsoft.ServiceBus.NamespaceManagerSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.#ctor(System.Collections.Generic.IEnumerable{System.String},Microsoft.ServiceBus.NamespaceManagerSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (addresses As IEnumerable(Of String), settings As NamespaceManagerSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NamespaceManager : seq&lt;string&gt; * Microsoft.ServiceBus.NamespaceManagerSettings -&gt; Microsoft.ServiceBus.NamespaceManager" Usage="new Microsoft.ServiceBus.NamespaceManager (addresses, settings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="settings" Type="Microsoft.ServiceBus.NamespaceManagerSettings" />
      </Parameters>
      <Docs>
        <param name="addresses"><span data-ttu-id="b9b6b-112">Die vollständige Adressen des dienstnamespaces.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-112">The full addresses of the service namespace.</span></span></param>
        <param name="settings"><span data-ttu-id="b9b6b-113">Ein <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> -Objekt, das enthält die <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.TokenProvider" /> und <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" /> Eigenschaften.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-113">A <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> object, which contains the <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.TokenProvider" /> and <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" /> properties.</span></span></param>
        <summary><span data-ttu-id="b9b6b-114">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> Klasse mit dem angegebenen Adressen und Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-114">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> class with the given addresses and settings.</span></span></summary>
        <remarks><span data-ttu-id="b9b6b-115">Obwohl es nicht zulässig ist, Pfade in der Namespace-Adresse enthalten, können Sie die Anmeldeinformationen, die nur auf einige Unterebenen von Basisadressen Aktionen autorisiert angeben, d. h. es ist kein, die die Anmeldeinformationen, die Sie angeben, auf der Basis Adressen Itse sein muss LF.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-115">Even though it is not allowed to include paths in the namespace address, you can specify a credential that authorizes you to perform actions only on some sublevels off of the base addresses, i.e. it is not a must that the credentials you specify be to the base adresses itself.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (System.Collections.Generic.IEnumerable&lt;string&gt; addresses, Microsoft.ServiceBus.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;string&gt; addresses, class Microsoft.ServiceBus.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.#ctor(System.Collections.Generic.IEnumerable{System.String},Microsoft.ServiceBus.TokenProvider)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NamespaceManager : seq&lt;string&gt; * Microsoft.ServiceBus.TokenProvider -&gt; Microsoft.ServiceBus.NamespaceManager" Usage="new Microsoft.ServiceBus.NamespaceManager (addresses, tokenProvider)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="tokenProvider" Type="Microsoft.ServiceBus.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="addresses"><span data-ttu-id="b9b6b-116">Die vollständige Adressen des dienstnamespaces.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-116">The full addresses of the service namespace.</span></span></param>
        <param name="tokenProvider"><span data-ttu-id="b9b6b-117">Der Sicherheitstokenanbieter.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-117">The security token provider.</span></span></param>
        <summary><span data-ttu-id="b9b6b-118">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> Klasse mit dem angegebenen Adressen und Anbieter von Sicherheitstoken.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-118">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> class with the given addresses and token provider.</span></span></summary>
        <remarks><span data-ttu-id="b9b6b-119">Obwohl es nicht zulässig ist die Namespace-Adressen Pfade einschließt, können Sie Anmeldeinformationen angeben, die nur auf einige Unterebenen von Basisadressen Aktionen autorisiert.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-119">Even though it is not allowed to include paths in the namespace addresses, you can specify a credential that authorizes you to perform actions only on some sublevels off of the base addresses.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (System.Collections.Generic.IEnumerable&lt;Uri&gt; addresses, Microsoft.ServiceBus.NamespaceManagerSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; addresses, class Microsoft.ServiceBus.NamespaceManagerSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.#ctor(System.Collections.Generic.IEnumerable{System.Uri},Microsoft.ServiceBus.NamespaceManagerSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (addresses As IEnumerable(Of Uri), settings As NamespaceManagerSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NamespaceManager : seq&lt;Uri&gt; * Microsoft.ServiceBus.NamespaceManagerSettings -&gt; Microsoft.ServiceBus.NamespaceManager" Usage="new Microsoft.ServiceBus.NamespaceManager (addresses, settings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="settings" Type="Microsoft.ServiceBus.NamespaceManagerSettings" />
      </Parameters>
      <Docs>
        <param name="addresses"><span data-ttu-id="b9b6b-120">Der vollständige URI-Adressen des dienstnamespaces.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-120">The full URI addresses of the service namespace.</span></span></param>
        <param name="settings"><span data-ttu-id="b9b6b-121">Ein <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> -Objekt, das enthält die <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.TokenProvider" /> und <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" /> Eigenschaften.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-121">A <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> object, which contains the <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.TokenProvider" /> and <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" /> properties.</span></span></param>
        <summary><span data-ttu-id="b9b6b-122">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> Klasse mit dem angegebenen Dienst Namespace-URI-Basisadressen und Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-122">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> class with the given service namespace URI base addresses and settings.</span></span></summary>
        <remarks><span data-ttu-id="b9b6b-123">Obwohl es nicht zulässig ist die Namespace-Adressen Pfade einschließt, können Sie die Anmeldeinformationen, die nur auf einige Unterebenen von Basisadressen Aktionen autorisiert angeben, d. h. es ist nicht erforderlich, dass die Anmeldeinformationen, die Sie angeben, auf der Basis-Adressen werden Self-Service.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-123">Even though it is not allowed to include paths in the namespace addresses, you can specify a credential that authorizes you to perform actions only on some sublevels off of the base addresses, i.e. it is not a must that the credentials you specify be to the base adresses itself.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (System.Collections.Generic.IEnumerable&lt;Uri&gt; addresses, Microsoft.ServiceBus.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; addresses, class Microsoft.ServiceBus.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.#ctor(System.Collections.Generic.IEnumerable{System.Uri},Microsoft.ServiceBus.TokenProvider)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NamespaceManager : seq&lt;Uri&gt; * Microsoft.ServiceBus.TokenProvider -&gt; Microsoft.ServiceBus.NamespaceManager" Usage="new Microsoft.ServiceBus.NamespaceManager (addresses, tokenProvider)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="tokenProvider" Type="Microsoft.ServiceBus.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="addresses"><span data-ttu-id="b9b6b-124">Der vollständige URI-Adressen des dienstnamespaces.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-124">The full URI addresses of the service namespace.</span></span></param>
        <param name="tokenProvider"><span data-ttu-id="b9b6b-125">Der Sicherheitstokenanbieter.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-125">The security token provider.</span></span></param>
        <summary><span data-ttu-id="b9b6b-126">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> Klasse mit dem angegebenen Dienst Namespace-URI-Basisadressen und Anbieter von Sicherheitstoken.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-126">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> class with the given service namespace URI base addresses and token provider.</span></span></summary>
        <remarks><span data-ttu-id="b9b6b-127">Obwohl es nicht zulässig ist die Namespace-Adressen Pfade einschließt, können Sie die Anmeldeinformationen, die nur auf einige Unterebenen von Basisadressen Aktionen autorisiert angeben, d. h. es ist nicht erforderlich, dass die Anmeldeinformationen, die Sie angeben, auf der Basis-Adressen werden Self-Service.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-127">Even though it is not allowed to include paths in the namespace addresses, you can specify a credential that authorizes you to perform actions only on some sublevels off of the base addresses, i.e. it is not a must that the credentials you specify be to the base adresses itself.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (string address, Microsoft.ServiceBus.NamespaceManagerSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string address, class Microsoft.ServiceBus.NamespaceManagerSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.#ctor(System.String,Microsoft.ServiceBus.NamespaceManagerSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (address As String, settings As NamespaceManagerSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NamespaceManager : string * Microsoft.ServiceBus.NamespaceManagerSettings -&gt; Microsoft.ServiceBus.NamespaceManager" Usage="new Microsoft.ServiceBus.NamespaceManager (address, settings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
        <Parameter Name="settings" Type="Microsoft.ServiceBus.NamespaceManagerSettings" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="b9b6b-128">Die vollständige Adresse des dienstnamespaces.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-128">The full address of the service namespace.</span></span></param>
        <param name="settings"><span data-ttu-id="b9b6b-129">Ein <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> -Objekt, das enthält die <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.TokenProvider" /> und <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" /> Eigenschaften.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-129">A <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> object, which contains the <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.TokenProvider" /> and <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" /> properties.</span></span></param>
        <summary><span data-ttu-id="b9b6b-130">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> Klasse mit dem angegebenen Namespace dienstbasisadresse und <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-130">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> class with the given service namespace base address and <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> object.</span></span></summary>
        <remarks><span data-ttu-id="b9b6b-131">Obwohl es nicht zulässig ist, Pfade in der Namespace-Adresse enthalten, können Sie die Anmeldeinformationen, die nur auf einige Unterebenen aus der Basisadresse Aktionen autorisiert angeben, d. h. es ist nicht erforderlich, die die Anmeldeinformationen, die Sie angeben, auf der Basis Adresse selbst sein.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-131">Even though it is not allowed to include paths in the namespace address, you can specify a credential that authorizes you to perform actions only on some sublevels off of the base address, i.e. it is not a must that the credentials you specify be to the base adress itself.</span></span></remarks>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="b9b6b-132"><paramref name="address" />enthält einen Pfad an die vollständige Adresse des Dienstnamespace angefügt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-132"><paramref name="address" /> contains a path appended to the full address of the service namespace.</span></span></exception>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="b9b6b-133"><paramref name="address" /> oder <paramref name="settings" /> ist NULL.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-133"><paramref name="address" /> or <paramref name="settings" /> is null.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (string address, Microsoft.ServiceBus.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string address, class Microsoft.ServiceBus.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.#ctor(System.String,Microsoft.ServiceBus.TokenProvider)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NamespaceManager : string * Microsoft.ServiceBus.TokenProvider -&gt; Microsoft.ServiceBus.NamespaceManager" Usage="new Microsoft.ServiceBus.NamespaceManager (address, tokenProvider)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
        <Parameter Name="tokenProvider" Type="Microsoft.ServiceBus.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="b9b6b-134">Die vollständige Adresse des dienstnamespaces.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-134">The full address of the service namespace.</span></span></param>
        <param name="tokenProvider"><span data-ttu-id="b9b6b-135">Der Sicherheitstokenanbieter.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-135">The security token provider.</span></span></param>
        <summary><span data-ttu-id="b9b6b-136">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> Klasse mit dem angegebenen Namespace dienstbasisadresse und Anbieter von Sicherheitstoken.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-136">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> class with the given service namespace base address and token provider.</span></span></summary>
        <remarks><span data-ttu-id="b9b6b-137">Obwohl es nicht zulässig ist, Pfade in der Namespace-Adresse enthalten, können Sie Anmeldeinformationen angeben, die nur auf einige Unterebenen aus der Basisadresse Aktionen autorisiert.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-137">Even though it is not allowed to include paths in the namespace address, you can specify a credential that authorizes you to perform actions only on some sublevels off of the base address.</span></span></remarks>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="b9b6b-138"><paramref name="address" />enthält einen Pfad an die vollständige Adresse des Dienstnamespace angefügt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-138"><paramref name="address" /> contains a path appended to the full address of the service namespace.</span></span></exception>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="b9b6b-139"><paramref name="address" /> oder <paramref name="tokenProvider" /> ist NULL.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-139"><paramref name="address" /> or <paramref name="tokenProvider" /> is null.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (Uri address, Microsoft.ServiceBus.NamespaceManagerSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri address, class Microsoft.ServiceBus.NamespaceManagerSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.#ctor(System.Uri,Microsoft.ServiceBus.NamespaceManagerSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (address As Uri, settings As NamespaceManagerSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NamespaceManager : Uri * Microsoft.ServiceBus.NamespaceManagerSettings -&gt; Microsoft.ServiceBus.NamespaceManager" Usage="new Microsoft.ServiceBus.NamespaceManager (address, settings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
        <Parameter Name="settings" Type="Microsoft.ServiceBus.NamespaceManagerSettings" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="b9b6b-140">Die vollständige URI-Adresse des dienstnamespaces.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-140">The full URI address of the service namespace.</span></span></param>
        <param name="settings"><span data-ttu-id="b9b6b-141">Ein <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> -Objekt, das enthält die <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.TokenProvider" /> und <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" /> Eigenschaften.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-141">A <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> object, which contains the <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.TokenProvider" /> and <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" /> properties.</span></span></param>
        <summary><span data-ttu-id="b9b6b-142">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> Klasse mit der angegebenen Service Namespace-URI-Basisadresse und <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-142">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> class with the given service namespace URI base address and <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> object.</span></span></summary>
        <remarks><span data-ttu-id="b9b6b-143">Obwohl es nicht zulässig ist, Pfade in der Namespace-Adresse enthalten, können Sie die Anmeldeinformationen, die nur auf einige Unterebenen aus der Basisadresse Aktionen autorisiert angeben, d. h. es ist nicht erforderlich, die die Anmeldeinformationen, die Sie angeben, auf der Basis Adresse selbst sein.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-143">Even though it is not allowed to include paths in the namespace address, you can specify a credential that authorizes you to perform actions only on some sublevels off of the base address, i.e. it is not a must that the credentials you specify be to the base adress itself.</span></span></remarks>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="b9b6b-144"><paramref name="address" />enthält einen Pfad an die vollständige Adresse des Dienstnamespace angefügt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-144"><paramref name="address" /> contains a path appended to the full address of the service namespace.</span></span></exception>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="b9b6b-145"><paramref name="address" /> oder <paramref name="settings" /> ist NULL.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-145"><paramref name="address" /> or <paramref name="settings" /> is null.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (Uri address, Microsoft.ServiceBus.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri address, class Microsoft.ServiceBus.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.#ctor(System.Uri,Microsoft.ServiceBus.TokenProvider)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NamespaceManager : Uri * Microsoft.ServiceBus.TokenProvider -&gt; Microsoft.ServiceBus.NamespaceManager" Usage="new Microsoft.ServiceBus.NamespaceManager (address, tokenProvider)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
        <Parameter Name="tokenProvider" Type="Microsoft.ServiceBus.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="b9b6b-146">Die vollständige URI-Adresse des dienstnamespaces.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-146">The full URI address of the service namespace.</span></span></param>
        <param name="tokenProvider"><span data-ttu-id="b9b6b-147">Das Sicherheitsobjekt Tokenanbieter.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-147">The security token provider object.</span></span></param>
        <summary><span data-ttu-id="b9b6b-148">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> Klasse mit der angegebenen Service Namespace-URI-Basisadresse und <see cref="T:Microsoft.ServiceBus.TokenProvider" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-148">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> class with the given service namespace URI base address and <see cref="T:Microsoft.ServiceBus.TokenProvider" /> object.</span></span></summary>
        <remarks><span data-ttu-id="b9b6b-149">Obwohl es nicht zulässig ist, Pfade in der Namespace-Adresse enthalten, können Sie die Anmeldeinformationen, die nur auf einige Unterebenen aus der Basisadresse Aktionen autorisiert angeben, d. h. es ist nicht erforderlich, die die Anmeldeinformationen, die Sie angeben, auf der Basis Adresse selbst sein.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-149">Even though it is not allowed to include paths in the namespace address, you can specify a credential that authorizes you to perform actions only on some sublevels off of the base address, i.e. it is not a must that the credentials you specify be to the base adress itself.</span></span></remarks>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="b9b6b-150"><paramref name="address" />enthält einen Pfad an die vollständige Adresse des Dienstnamespace angefügt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-150"><paramref name="address" /> contains a path appended to the full address of the service namespace.</span></span></exception>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="b9b6b-151"><paramref name="address" /> oder <paramref name="tokenProvider" /> ist NULL.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-151"><paramref name="address" /> or <paramref name="tokenProvider" /> is null.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Address">
      <MemberSignature Language="C#" Value="public Uri Address { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Address" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NamespaceManager.Address" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Address As Uri" />
      <MemberSignature Language="F#" Value="member this.Address : Uri" Usage="Microsoft.ServiceBus.NamespaceManager.Address" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="b9b6b-152">Ruft die Basisadresse des Diensts-Namespace ab.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-152">Gets the service namespace base address.</span></span></summary>
        <value><span data-ttu-id="b9b6b-153">Ein <see cref="T:System.Uri" /> , der die Basisadresse des Diensts Namespace darstellt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-153">A <see cref="T:System.Uri" /> that represents the service namespace base address.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.NamespaceManager Create ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.NamespaceManager Create() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.Create" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create () As NamespaceManager" />
      <MemberSignature Language="F#" Value="static member Create : unit -&gt; Microsoft.ServiceBus.NamespaceManager" Usage="Microsoft.ServiceBus.NamespaceManager.Create " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.NamespaceManager</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="b9b6b-154">Erstellt eine neue Instanz von <see cref="T:Microsoft.ServiceBus.NamespaceManager" />.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-154">Creates a new instance of <see cref="T:Microsoft.ServiceBus.NamespaceManager" />.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-155">Eine neue Instanz von <see cref="T:Microsoft.ServiceBus.NamespaceManager" />.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-155">A new instance of <see cref="T:Microsoft.ServiceBus.NamespaceManager" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateConsumerGroup">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.ConsumerGroupDescription CreateConsumerGroup (Microsoft.ServiceBus.Messaging.ConsumerGroupDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription CreateConsumerGroup(class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateConsumerGroup(Microsoft.ServiceBus.Messaging.ConsumerGroupDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateConsumerGroup (description As ConsumerGroupDescription) As ConsumerGroupDescription" />
      <MemberSignature Language="F#" Value="member this.CreateConsumerGroup : Microsoft.ServiceBus.Messaging.ConsumerGroupDescription -&gt; Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" Usage="namespaceManager.CreateConsumerGroup description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.ConsumerGroupDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="b9b6b-156">Die <see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-156">The <see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />.</span></span></param>
        <summary><span data-ttu-id="b9b6b-157">Erstellt eine Event Hubs-Consumer-Gruppe unter Verwendung des angegebenen <see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-157">Creates an Event Hubs consumer group using the specified <see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-158">Gibt <see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />zurück.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-158">Returns <see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateConsumerGroup">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.ConsumerGroupDescription CreateConsumerGroup (string eventHubPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription CreateConsumerGroup(string eventHubPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateConsumerGroup(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateConsumerGroup (eventHubPath As String, name As String) As ConsumerGroupDescription" />
      <MemberSignature Language="F#" Value="member this.CreateConsumerGroup : string * string -&gt; Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" Usage="namespaceManager.CreateConsumerGroup (eventHubPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.ConsumerGroupDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventHubPath"><span data-ttu-id="b9b6b-159">Der Pfad zu den Event Hub.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-159">The path to the Event Hub.</span></span></param>
        <param name="name"><span data-ttu-id="b9b6b-160">Der Name der Gruppe "Consumer".</span><span class="sxs-lookup"><span data-stu-id="b9b6b-160">The name of the consumer group.</span></span></param>
        <summary><span data-ttu-id="b9b6b-161">Erstellt eine Event Hubs-Consumer-Gruppe mit Default-Werten, mit der angegebenen Event Hubs-Pfad und einen Namen für die consumergruppe.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-161">Creates an Event Hubs consumer group using default values, with the specified Event Hubs path and a name for the consumer group.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-162">Gibt <see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />zurück.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-162">Returns <see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateConsumerGroupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt; CreateConsumerGroupAsync (Microsoft.ServiceBus.Messaging.ConsumerGroupDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt; CreateConsumerGroupAsync(class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateConsumerGroupAsync(Microsoft.ServiceBus.Messaging.ConsumerGroupDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateConsumerGroupAsync (description As ConsumerGroupDescription) As Task(Of ConsumerGroupDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateConsumerGroupAsync : Microsoft.ServiceBus.Messaging.ConsumerGroupDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;" Usage="namespaceManager.CreateConsumerGroupAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="b9b6b-163">Die <see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-163">The <see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />.</span></span></param>
        <summary><span data-ttu-id="b9b6b-164">Asynchrone Version von <see cref="M:Microsoft.ServiceBus.NamespaceManager.CreateConsumerGroup(Microsoft.ServiceBus.Messaging.ConsumerGroupDescription)" />.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-164">Asynchronous version of <see cref="M:Microsoft.ServiceBus.NamespaceManager.CreateConsumerGroup(Microsoft.ServiceBus.Messaging.ConsumerGroupDescription)" />.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-165">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-165">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateConsumerGroupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt; CreateConsumerGroupAsync (string eventHubPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt; CreateConsumerGroupAsync(string eventHubPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateConsumerGroupAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateConsumerGroupAsync (eventHubPath As String, name As String) As Task(Of ConsumerGroupDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateConsumerGroupAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;" Usage="namespaceManager.CreateConsumerGroupAsync (eventHubPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventHubPath"><span data-ttu-id="b9b6b-166">Der Pfad zu den Event Hub.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-166">The path to the Event Hub.</span></span></param>
        <param name="name"><span data-ttu-id="b9b6b-167">Der Name der Gruppe "Consumer".</span><span class="sxs-lookup"><span data-stu-id="b9b6b-167">The name of the consumer group.</span></span></param>
        <summary><span data-ttu-id="b9b6b-168">Asynchrone Version von <see cref="M:Microsoft.ServiceBus.NamespaceManager.CreateConsumerGroup(System.String,System.String)" />.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-168">Asynchronous version of <see cref="M:Microsoft.ServiceBus.NamespaceManager.CreateConsumerGroup(System.String,System.String)" />.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-169">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-169">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateConsumerGroupIfNotExists">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.ConsumerGroupDescription CreateConsumerGroupIfNotExists (Microsoft.ServiceBus.Messaging.ConsumerGroupDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription CreateConsumerGroupIfNotExists(class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateConsumerGroupIfNotExists(Microsoft.ServiceBus.Messaging.ConsumerGroupDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateConsumerGroupIfNotExists (description As ConsumerGroupDescription) As ConsumerGroupDescription" />
      <MemberSignature Language="F#" Value="member this.CreateConsumerGroupIfNotExists : Microsoft.ServiceBus.Messaging.ConsumerGroupDescription -&gt; Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" Usage="namespaceManager.CreateConsumerGroupIfNotExists description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.ConsumerGroupDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="b9b6b-170">Ein <see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-170">A <see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" /> object.</span></span></param>
        <summary><span data-ttu-id="b9b6b-171">Eine consumergruppe erstellt, wenn er nicht bereits unter Verwendung des angegebenen vorhanden ist, <see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" /> als Metadaten.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-171">Creates a consumer group if it does not already exist, using the specified <see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" /> as metadata.</span></span> <span data-ttu-id="b9b6b-172">Wenn die Gruppe bereits vorhanden ist, klicken Sie dann zurück gespeicherten <see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-172">If the group already exists, then return the stored <see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-173">Gibt zurück, die neu erstellte <see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-173">Returns the newly-created <see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />.</span></span> <span data-ttu-id="b9b6b-174">Wenn die consumergruppe bereits vorhanden ist, gibt die vorhandene <see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-174">If the consumer group already exists, returns the existing <see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateConsumerGroupIfNotExists">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.ConsumerGroupDescription CreateConsumerGroupIfNotExists (string eventHubPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription CreateConsumerGroupIfNotExists(string eventHubPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateConsumerGroupIfNotExists(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateConsumerGroupIfNotExists (eventHubPath As String, name As String) As ConsumerGroupDescription" />
      <MemberSignature Language="F#" Value="member this.CreateConsumerGroupIfNotExists : string * string -&gt; Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" Usage="namespaceManager.CreateConsumerGroupIfNotExists (eventHubPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.ConsumerGroupDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventHubPath"><span data-ttu-id="b9b6b-175">Pfad zu den Event Hub.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-175">Path to the Event Hub.</span></span></param>
        <param name="name"><span data-ttu-id="b9b6b-176">Der Name der Gruppe "Consumer" zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-176">The name of the consumer group to create.</span></span></param>
        <summary><span data-ttu-id="b9b6b-177">Erstellt eine consumergruppe, wenn er nicht bereits mit dem angegebenen Namen von Event Hubs Pfad und der Gruppe vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-177">Creates a consumer group if it does not already exist, using the specified Event Hubs path and group name.</span></span> <span data-ttu-id="b9b6b-178">Wenn die Gruppe bereits vorhanden ist, klicken Sie dann zurück gespeicherten <see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-178">If the group already exists, then return the stored <see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-179">Gibt zurück, die neu erstellte <see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-179">Returns the newly-created <see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />.</span></span> <span data-ttu-id="b9b6b-180">Wenn die consumergruppe bereits vorhanden ist, gibt die vorhandene <see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-180">If the consumer group already exists, returns the existing <see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateConsumerGroupIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt; CreateConsumerGroupIfNotExistsAsync (Microsoft.ServiceBus.Messaging.ConsumerGroupDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt; CreateConsumerGroupIfNotExistsAsync(class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateConsumerGroupIfNotExistsAsync(Microsoft.ServiceBus.Messaging.ConsumerGroupDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateConsumerGroupIfNotExistsAsync (description As ConsumerGroupDescription) As Task(Of ConsumerGroupDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateConsumerGroupIfNotExistsAsync : Microsoft.ServiceBus.Messaging.ConsumerGroupDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;" Usage="namespaceManager.CreateConsumerGroupIfNotExistsAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="b9b6b-181">Die Beschreibung für den Consumer-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-181">The consumer group description.</span></span></param>
        <summary><span data-ttu-id="b9b6b-182">Asynchrone Version von <see cref="M:Microsoft.ServiceBus.NamespaceManager.CreateConsumerGroupIfNotExists(Microsoft.ServiceBus.Messaging.ConsumerGroupDescription)" />.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-182">Asynchronous version of <see cref="M:Microsoft.ServiceBus.NamespaceManager.CreateConsumerGroupIfNotExists(Microsoft.ServiceBus.Messaging.ConsumerGroupDescription)" />.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-183">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-183">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateConsumerGroupIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt; CreateConsumerGroupIfNotExistsAsync (string eventHubPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt; CreateConsumerGroupIfNotExistsAsync(string eventHubPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateConsumerGroupIfNotExistsAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateConsumerGroupIfNotExistsAsync (eventHubPath As String, name As String) As Task(Of ConsumerGroupDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateConsumerGroupIfNotExistsAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;" Usage="namespaceManager.CreateConsumerGroupIfNotExistsAsync (eventHubPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventHubPath"><span data-ttu-id="b9b6b-184">Der Pfad zu den Event Hub.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-184">The path to the Event Hub.</span></span></param>
        <param name="name"><span data-ttu-id="b9b6b-185">Der Name der Gruppe "Consumer".</span><span class="sxs-lookup"><span data-stu-id="b9b6b-185">The name of the consumer group.</span></span></param>
        <summary><span data-ttu-id="b9b6b-186">Asynchrone Version von <see cref="M:Microsoft.ServiceBus.NamespaceManager.CreateConsumerGroupIfNotExists(System.String,System.String)" />.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-186">Asynchronous version of <see cref="M:Microsoft.ServiceBus.NamespaceManager.CreateConsumerGroupIfNotExists(System.String,System.String)" />.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-187">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-187">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateEventHub">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventHubDescription CreateEventHub (Microsoft.ServiceBus.Messaging.EventHubDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventHubDescription CreateEventHub(class Microsoft.ServiceBus.Messaging.EventHubDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateEventHub(Microsoft.ServiceBus.Messaging.EventHubDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateEventHub (description As EventHubDescription) As EventHubDescription" />
      <MemberSignature Language="F#" Value="member this.CreateEventHub : Microsoft.ServiceBus.Messaging.EventHubDescription -&gt; Microsoft.ServiceBus.Messaging.EventHubDescription" Usage="namespaceManager.CreateEventHub description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.EventHubDescription" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="b9b6b-188">Die <see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" />.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-188">The <see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" />.</span></span></param>
        <summary><span data-ttu-id="b9b6b-189">Erstellt einen neuen Event Hub mithilfe des angegebenen <see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" />.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-189">Creates a new Event Hub using the specified <see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" />.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-190">Gibt <see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" /> zurück.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-190">Returns the <see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateEventHub">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventHubDescription CreateEventHub (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventHubDescription CreateEventHub(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateEventHub(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateEventHub (path As String) As EventHubDescription" />
      <MemberSignature Language="F#" Value="member this.CreateEventHub : string -&gt; Microsoft.ServiceBus.Messaging.EventHubDescription" Usage="namespaceManager.CreateEventHub path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="b9b6b-191">Der Pfad zu den Event Hub.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-191">The path to the Event Hub.</span></span></param>
        <summary><span data-ttu-id="b9b6b-192">Erstellt einen neuen Event Hub mit Standardwerten, für der angegebene Eingabepfad an.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-192">Creates a new Event Hub using default values, for the given input path.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-193">Gibt <see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" /> zurück.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-193">Returns the <see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateEventHubAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt; CreateEventHubAsync (Microsoft.ServiceBus.Messaging.EventHubDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.EventHubDescription&gt; CreateEventHubAsync(class Microsoft.ServiceBus.Messaging.EventHubDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateEventHubAsync(Microsoft.ServiceBus.Messaging.EventHubDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateEventHubAsync (description As EventHubDescription) As Task(Of EventHubDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateEventHubAsync : Microsoft.ServiceBus.Messaging.EventHubDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt;" Usage="namespaceManager.CreateEventHubAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.EventHubDescription" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="b9b6b-194">Ein <see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" /> Objekt, das den Event Hub erstellen beschreibt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-194">An <see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" /> object that describes the Event Hub to create.</span></span></param>
        <summary><span data-ttu-id="b9b6b-195">Erstellt asynchron einen Event Hub.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-195">Asynchronously creates an event hub.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-196">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-196">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateEventHubAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt; CreateEventHubAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.EventHubDescription&gt; CreateEventHubAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateEventHubAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateEventHubAsync (path As String) As Task(Of EventHubDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateEventHubAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt;" Usage="namespaceManager.CreateEventHubAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="b9b6b-197">Der Pfad zu den Event Hub.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-197">The path to the Event Hub.</span></span></param>
        <summary><span data-ttu-id="b9b6b-198">Erstellt asynchron einen Event Hub.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-198">Asynchronously creates an event hub.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-199">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-199">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateEventHubIfNotExists">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventHubDescription CreateEventHubIfNotExists (Microsoft.ServiceBus.Messaging.EventHubDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventHubDescription CreateEventHubIfNotExists(class Microsoft.ServiceBus.Messaging.EventHubDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateEventHubIfNotExists(Microsoft.ServiceBus.Messaging.EventHubDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateEventHubIfNotExists (description As EventHubDescription) As EventHubDescription" />
      <MemberSignature Language="F#" Value="member this.CreateEventHubIfNotExists : Microsoft.ServiceBus.Messaging.EventHubDescription -&gt; Microsoft.ServiceBus.Messaging.EventHubDescription" Usage="namespaceManager.CreateEventHubIfNotExists description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.EventHubDescription" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="b9b6b-200">Ein <see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" /> Objekt, das den Event Hub erstellen beschreibt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-200">An <see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" /> object that describes the Event Hub to create.</span></span></param>
        <summary><span data-ttu-id="b9b6b-201">Erstellt einen Event Hub an, wenn er nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-201">Creates an Event Hub if it does not exist.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-202">Gibt ein<see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-202">Returns an<see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateEventHubIfNotExists">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventHubDescription CreateEventHubIfNotExists (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventHubDescription CreateEventHubIfNotExists(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateEventHubIfNotExists(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateEventHubIfNotExists (path As String) As EventHubDescription" />
      <MemberSignature Language="F#" Value="member this.CreateEventHubIfNotExists : string -&gt; Microsoft.ServiceBus.Messaging.EventHubDescription" Usage="namespaceManager.CreateEventHubIfNotExists path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="b9b6b-203">Der Pfad zu den Event Hub.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-203">The path to the Event Hub.</span></span></param>
        <summary><span data-ttu-id="b9b6b-204">Erstellt einen Event Hub an, wenn er nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-204">Creates an Event Hub if it does not exist.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-205">Gibt ein <see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-205">Returns an <see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateEventHubIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt; CreateEventHubIfNotExistsAsync (Microsoft.ServiceBus.Messaging.EventHubDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.EventHubDescription&gt; CreateEventHubIfNotExistsAsync(class Microsoft.ServiceBus.Messaging.EventHubDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateEventHubIfNotExistsAsync(Microsoft.ServiceBus.Messaging.EventHubDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateEventHubIfNotExistsAsync (description As EventHubDescription) As Task(Of EventHubDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateEventHubIfNotExistsAsync : Microsoft.ServiceBus.Messaging.EventHubDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt;" Usage="namespaceManager.CreateEventHubIfNotExistsAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.EventHubDescription" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="b9b6b-206">Der Hub-Beschreibung des Ereignisses.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-206">The event hub description.</span></span></param>
        <summary><span data-ttu-id="b9b6b-207">Erstellt einen Event Hub asynchron, wenn er nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-207">Asynchronously creates an Event Hub if it does not exist.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-208">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-208">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateEventHubIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt; CreateEventHubIfNotExistsAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.EventHubDescription&gt; CreateEventHubIfNotExistsAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateEventHubIfNotExistsAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateEventHubIfNotExistsAsync (path As String) As Task(Of EventHubDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateEventHubIfNotExistsAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt;" Usage="namespaceManager.CreateEventHubIfNotExistsAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="b9b6b-209">Der Pfad des Event Hubs.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-209">The path of the event hub.</span></span></param>
        <summary><span data-ttu-id="b9b6b-210">Erstellt einen Event Hub asynchron, wenn er nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-210">Asynchronously creates an Event Hub if it does not exist.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-211">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-211">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.NamespaceManager CreateFromConnectionString (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.NamespaceManager CreateFromConnectionString(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateFromConnectionString(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String) As NamespaceManager" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string -&gt; Microsoft.ServiceBus.NamespaceManager" Usage="Microsoft.ServiceBus.NamespaceManager.CreateFromConnectionString connectionString" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.NamespaceManager</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="b9b6b-212">Verbindung unkompliziert verwendet.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-212">The connection sting used.</span></span></param>
        <summary><span data-ttu-id="b9b6b-213">Erstellt eine neue Instanz der <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> mithilfe der angegebenen Verbindungszeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-213">Creates a new instance of <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> using a specified connection string.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-214">Eine neue Instanz von <see cref="T:Microsoft.ServiceBus.NamespaceManager" />.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-214">A new instance of <see cref="T:Microsoft.ServiceBus.NamespaceManager" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateQueue">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.QueueDescription CreateQueue (Microsoft.ServiceBus.Messaging.QueueDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.QueueDescription CreateQueue(class Microsoft.ServiceBus.Messaging.QueueDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateQueue(Microsoft.ServiceBus.Messaging.QueueDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateQueue (description As QueueDescription) As QueueDescription" />
      <MemberSignature Language="F#" Value="member this.CreateQueue : Microsoft.ServiceBus.Messaging.QueueDescription -&gt; Microsoft.ServiceBus.Messaging.QueueDescription" Usage="namespaceManager.CreateQueue description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.QueueDescription" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="b9b6b-215">Ein <see cref="T:Microsoft.ServiceBus.Messaging.QueueDescription" /> -Objekt, beschreibt die Attribute, mit denen die neue Warteschlange erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-215">A <see cref="T:Microsoft.ServiceBus.Messaging.QueueDescription" /> object describing the attributes with which the new queue will be created.</span></span></param>
        <summary><span data-ttu-id="b9b6b-216">Erstellt eine neue Warteschlange im Dienstnamespace mit der angegebenen warteschlangenbeschreibung an.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-216">Creates a new queue in the service namespace with the specified queue description.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-217">Die <see cref="T:Microsoft.ServiceBus.Messaging.QueueDescription" /> der neu erstellten Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-217">The <see cref="T:Microsoft.ServiceBus.Messaging.QueueDescription" /> of the newly created queue.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateQueue">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.QueueDescription CreateQueue (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.QueueDescription CreateQueue(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateQueue(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateQueue (path As String) As QueueDescription" />
      <MemberSignature Language="F#" Value="member this.CreateQueue : string -&gt; Microsoft.ServiceBus.Messaging.QueueDescription" Usage="namespaceManager.CreateQueue path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="b9b6b-218">Der Pfad der Warteschlange relativ zur Basisadresse Diensts-Namespace.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-218">The path of the queue relative to the service namespace base address.</span></span></param>
        <summary><span data-ttu-id="b9b6b-219">Erstellt eine neue Warteschlange im Dienstnamespace mit dem angegebenen Pfad.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-219">Creates a new queue in the service namespace with the given path.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-220">Die <see cref="T:Microsoft.ServiceBus.Messaging.QueueDescription" /> der neu erstellten Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-220">The <see cref="T:Microsoft.ServiceBus.Messaging.QueueDescription" /> of the newly created queue.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="b9b6b-221"><paramref name="path" />ist null oder leer.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-221"><paramref name="path" /> is null or empty.</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="b9b6b-222">Die Länge des <paramref name="path" /> 290 Zeichen übersteigt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-222">The length of <paramref name="path" /> is greater than 290 characters.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="b9b6b-223">Timeout des Vorgangs. Das Zeitlimit wird initialisiert, durch die <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> Klasse.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-223">The operation times out. The timeout period is initialized through the <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> class.</span></span> <span data-ttu-id="b9b6b-224">Sie müssen möglicherweise den Wert erhöhen die <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" /> Eigenschaft, um diese Ausnahme zu vermeiden, wenn der Timeoutwert relativ gering ist.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-224">You may need to increase the value of the <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" /> property to avoid this exception if the timeout value is relatively low.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityAlreadyExistsException"><span data-ttu-id="b9b6b-225">Unter desselben Namespace befindet sich eine Warteschlange oder ein Thema mit dem gleichen Namen und Pfad.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-225">A queue or a topic with the same name and path exists under the same service namespace.</span></span></exception>
        <exception cref="T:System.UnauthorizedAccessException"><span data-ttu-id="b9b6b-226">Die <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> Objekt verfügt nicht über ausreichende Berechtigungen zum Ausführen dieses Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-226">The <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> object does not have sufficient permission to perform this operation.</span></span> <span data-ttu-id="b9b6b-227">Sie sollten prüfen, um sicherzustellen, dass Ihre <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> verfügt über den richtigen <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.TokenProvider" /> Anmeldeinformationen zum Ausführen dieses Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-227">You should check to ensure that your <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> has the correct <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.TokenProvider" /> credentials to perform this operation.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.QuotaExceededException"><span data-ttu-id="b9b6b-228">Die angegebene Größe in der Beschreibung wird nicht unterstützt oder die maximale zulässige Kontingent erreicht haben.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-228">Either the specified size in the description is not supported or the maximum allowable quota has been reached.</span></span> <span data-ttu-id="b9b6b-229">Sie müssen Geben Sie einen der unterstützten Größenwerte, löschen vorhandene Entitäten oder Ihr Kontingent vergrößern.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-229">You must specify one of the supported size values, delete existing entities, or increase your quota size.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException"><span data-ttu-id="b9b6b-230">Ein interner Fehler oder unerwartete Ausnahme auftritt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-230">An internal error or unexpected exception occurs.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ServerBusyException"><span data-ttu-id="b9b6b-231">Der Server wird mit logischen Operationen überladen.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-231">The server is overloaded with logical operations.</span></span> <span data-ttu-id="b9b6b-232">Sie können erwägen Sie keines der folgenden Aktionen: Warten Sie, und wiederholen Sie das Aufrufen dieser Funktion. Entfernen von Entitäten vor Wiederholung (z. B. Empfangen von Nachrichten vor dem Senden keine weiteren).</span><span class="sxs-lookup"><span data-stu-id="b9b6b-232">You can consider any of the following actions:Wait and retry calling this function.Remove entities before retry (for example, receive messages before sending any more).</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CreateQueueAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt; CreateQueueAsync (Microsoft.ServiceBus.Messaging.QueueDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.QueueDescription&gt; CreateQueueAsync(class Microsoft.ServiceBus.Messaging.QueueDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateQueueAsync(Microsoft.ServiceBus.Messaging.QueueDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateQueueAsync (description As QueueDescription) As Task(Of QueueDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateQueueAsync : Microsoft.ServiceBus.Messaging.QueueDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;" Usage="namespaceManager.CreateQueueAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.QueueDescription" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="b9b6b-233">Ein <see cref="T:Microsoft.ServiceBus.Messaging.QueueDescription" /> -Objekt, beschreibt die Attribute, mit denen die neue Warteschlange erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-233">A <see cref="T:Microsoft.ServiceBus.Messaging.QueueDescription" /> object describing the attributes with which the new queue will be created.</span></span></param>
        <summary><span data-ttu-id="b9b6b-234">Erstellt asynchron eine neue Warteschlange im Dienstnamespace mit der angegebenen warteschlangenbeschreibung ein.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-234">Asynchronously creates a new queue in the service namespace with the specified queue description.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-235">Die <see cref="T:Microsoft.ServiceBus.Messaging.QueueDescription" /> der neu erstellten Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-235">The <see cref="T:Microsoft.ServiceBus.Messaging.QueueDescription" /> of the newly created queue.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateQueueAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt; CreateQueueAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.QueueDescription&gt; CreateQueueAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateQueueAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateQueueAsync (path As String) As Task(Of QueueDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateQueueAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;" Usage="namespaceManager.CreateQueueAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="b9b6b-236">Der Pfad der Warteschlange relativ zur Basisadresse Diensts-Namespace.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-236">The path of the queue relative to the service namespace base address.</span></span></param>
        <summary><span data-ttu-id="b9b6b-237">Erstellt asynchron eine neue Warteschlange im Dienstnamespace mit dem angegebenen Pfad.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-237">Asynchronously creates a new queue in the service namespace with the given path.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-238">Die <see cref="T:Microsoft.ServiceBus.Messaging.QueueDescription" /> der neu erstellten Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-238">The <see cref="T:Microsoft.ServiceBus.Messaging.QueueDescription" /> of the newly created queue.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateRelay">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.RelayDescription CreateRelay (Microsoft.ServiceBus.Messaging.RelayDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.RelayDescription CreateRelay(class Microsoft.ServiceBus.Messaging.RelayDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateRelay(Microsoft.ServiceBus.Messaging.RelayDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateRelay (description As RelayDescription) As RelayDescription" />
      <MemberSignature Language="F#" Value="member this.CreateRelay : Microsoft.ServiceBus.Messaging.RelayDescription -&gt; Microsoft.ServiceBus.Messaging.RelayDescription" Usage="namespaceManager.CreateRelay description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.RelayDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.RelayDescription" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="b9b6b-239">Das Beschreibungsobjekt für beschreiben die Attribute, mit denen das neue Relay erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-239">The description object describing the attributes with which the new relay will be created.</span></span></param>
        <summary><span data-ttu-id="b9b6b-240">Erstellt ein neues Relay im Dienstnamespace mit dem angegebenen Relay-Beschreibung an.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-240">Creates a new relay in the service namespace with the specified relay description.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-241">Die <see cref="T:Microsoft.ServiceBus.Messaging.RelayDescription" /> Objekt für das neu erstellte Relay.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-241">The <see cref="T:Microsoft.ServiceBus.Messaging.RelayDescription" /> object for the newly created relay.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateRelay">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.RelayDescription CreateRelay (string path, Microsoft.ServiceBus.RelayType type);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.RelayDescription CreateRelay(string path, valuetype Microsoft.ServiceBus.RelayType type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateRelay(System.String,Microsoft.ServiceBus.RelayType)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateRelay (path As String, type As RelayType) As RelayDescription" />
      <MemberSignature Language="F#" Value="member this.CreateRelay : string * Microsoft.ServiceBus.RelayType -&gt; Microsoft.ServiceBus.Messaging.RelayDescription" Usage="namespaceManager.CreateRelay (path, type)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.RelayDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="type" Type="Microsoft.ServiceBus.RelayType" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="b9b6b-242">Der Pfad der Warteschlange relativ zur Basisadresse Diensts-Namespace.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-242">The path of the queue relative to the service namespace base address.</span></span></param>
        <param name="type"><span data-ttu-id="b9b6b-243">Der Relay-Typ.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-243">The relay type.</span></span></param>
        <summary><span data-ttu-id="b9b6b-244">Erstellt ein neues Relay im Dienstnamespace mit dem angegebenen Pfad und den Typ an.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-244">Creates a new relay in the service namespace with the given path and type.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-245">Die <see cref="T:Microsoft.ServiceBus.Messaging.RelayDescription" /> Objekt für das neu erstellte Relay.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-245">The <see cref="T:Microsoft.ServiceBus.Messaging.RelayDescription" /> object for the newly created relay.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateRelayAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt; CreateRelayAsync (Microsoft.ServiceBus.Messaging.RelayDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.RelayDescription&gt; CreateRelayAsync(class Microsoft.ServiceBus.Messaging.RelayDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateRelayAsync(Microsoft.ServiceBus.Messaging.RelayDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateRelayAsync (description As RelayDescription) As Task(Of RelayDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateRelayAsync : Microsoft.ServiceBus.Messaging.RelayDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt;" Usage="namespaceManager.CreateRelayAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.RelayDescription" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="b9b6b-246">Das Beschreibungsobjekt für beschreiben die Attribute, mit denen das neue Relay erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-246">The description object describing the attributes with which the new relay will be created.</span></span></param>
        <summary><span data-ttu-id="b9b6b-247">Erstellt asynchron ein neues Relay im Dienstnamespace mit dem angegebenen Relay-Beschreibung an.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-247">Asynchronously creates a new relay in the service namespace with the specified relay description.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-248">Die <see cref="T:Microsoft.ServiceBus.Messaging.RelayDescription" /> Objekt für das neu erstellte Relay.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-248">The <see cref="T:Microsoft.ServiceBus.Messaging.RelayDescription" /> object for the newly created relay.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateRelayAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt; CreateRelayAsync (string path, Microsoft.ServiceBus.RelayType type);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.RelayDescription&gt; CreateRelayAsync(string path, valuetype Microsoft.ServiceBus.RelayType type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateRelayAsync(System.String,Microsoft.ServiceBus.RelayType)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateRelayAsync (path As String, type As RelayType) As Task(Of RelayDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateRelayAsync : string * Microsoft.ServiceBus.RelayType -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt;" Usage="namespaceManager.CreateRelayAsync (path, type)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="type" Type="Microsoft.ServiceBus.RelayType" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="b9b6b-249">Der Pfad der Warteschlange relativ zur Basisadresse Diensts-Namespace.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-249">The path of the queue relative to the service namespace base address.</span></span></param>
        <param name="type"><span data-ttu-id="b9b6b-250">Der Relay-Typ.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-250">The relay type.</span></span></param>
        <summary><span data-ttu-id="b9b6b-251">Erstellt asynchron ein neues Relay im Dienstnamespace mit dem angegebenen Pfad und den Typ an.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-251">Asynchronously creates a new relay in the service namespace with the given path and type.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-252">Die <see cref="T:Microsoft.ServiceBus.Messaging.RelayDescription" /> Objekt für das neu erstellte Relay.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-252">The <see cref="T:Microsoft.ServiceBus.Messaging.RelayDescription" /> object for the newly created relay.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSubscription">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.SubscriptionDescription CreateSubscription (Microsoft.ServiceBus.Messaging.SubscriptionDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.SubscriptionDescription CreateSubscription(class Microsoft.ServiceBus.Messaging.SubscriptionDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateSubscription(Microsoft.ServiceBus.Messaging.SubscriptionDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateSubscription (description As SubscriptionDescription) As SubscriptionDescription" />
      <MemberSignature Language="F#" Value="member this.CreateSubscription : Microsoft.ServiceBus.Messaging.SubscriptionDescription -&gt; Microsoft.ServiceBus.Messaging.SubscriptionDescription" Usage="namespaceManager.CreateSubscription description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.SubscriptionDescription" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="b9b6b-253">Ein <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> -Objekt, beschreibt die Attribute, mit denen das neue Abonnement erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-253">A <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> object describing the attributes with which the new subscription will be created.</span></span></param>
        <summary><span data-ttu-id="b9b6b-254">Erstellt ein neues Abonnement im Dienstnamespace mit der Beschreibung angegebenen Abonnement.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-254">Creates a new subscription in the service namespace with the specified subscription description.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-255">Die <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> des neu erstellten Abonnements.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-255">The <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> of the newly created subscription.</span></span></returns>
        <remarks> <span data-ttu-id="b9b6b-256">Standardmäßig wird ein Filter "Pass-Through" für dieses Abonnement erstellt dies, dass er alle Nachrichten bedeutet zu diesem Abonnement gesendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-256">Be default, A "pass-through" filter is created for this subscription, which means it will allow all message to go to this subscription.</span></span> <span data-ttu-id="b9b6b-257">Der Name des Filters ist <see cref="F:Microsoft.ServiceBus.Messaging.RuleDescription.DefaultRuleName" />.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-257">The name of the filter is <see cref="F:Microsoft.ServiceBus.Messaging.RuleDescription.DefaultRuleName" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSubscription">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.SubscriptionDescription CreateSubscription (Microsoft.ServiceBus.Messaging.SubscriptionDescription description, Microsoft.ServiceBus.Messaging.Filter filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.SubscriptionDescription CreateSubscription(class Microsoft.ServiceBus.Messaging.SubscriptionDescription description, class Microsoft.ServiceBus.Messaging.Filter filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateSubscription(Microsoft.ServiceBus.Messaging.SubscriptionDescription,Microsoft.ServiceBus.Messaging.Filter)" />
      <MemberSignature Language="F#" Value="member this.CreateSubscription : Microsoft.ServiceBus.Messaging.SubscriptionDescription * Microsoft.ServiceBus.Messaging.Filter -&gt; Microsoft.ServiceBus.Messaging.SubscriptionDescription" Usage="namespaceManager.CreateSubscription (description, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.SubscriptionDescription" />
        <Parameter Name="filter" Type="Microsoft.ServiceBus.Messaging.Filter" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="b9b6b-258">Ein <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> -Objekt, beschreibt die Attribute, mit denen das neue Abonnement erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-258">A <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> object describing the attributes with which the new subscription will be created.</span></span></param>
        <param name="filter"><span data-ttu-id="b9b6b-259">Der Filterausdruck, der zur Erfassung von Nachrichten, die den Filterwert Ausdruck erfüllen.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-259">The filter expression used to capture messages satisfying the filtering expression value.</span></span></param>
        <summary><span data-ttu-id="b9b6b-260">Erstellt ein neues Abonnement im Dienstnamespace mit dem angegebenen abonnementbeschreibung und den Filterausdruck an.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-260">Creates a new subscription in the service namespace with the specified subscription description and filter expression.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-261">Die <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> des neu erstellten Abonnements.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-261">The <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> of the newly created subscription.</span></span></returns>
        <remarks> <span data-ttu-id="b9b6b-262">Eine Standardregel erstellt, die mit Daten aus <paramref name="filter" /> und als benannte <see cref="F:Microsoft.ServiceBus.Messaging.RuleDescription.DefaultRuleName" />.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-262">A default rule will be created using data from <paramref name="filter" /> and named as <see cref="F:Microsoft.ServiceBus.Messaging.RuleDescription.DefaultRuleName" />.</span></span> </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSubscription">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.SubscriptionDescription CreateSubscription (Microsoft.ServiceBus.Messaging.SubscriptionDescription description, Microsoft.ServiceBus.Messaging.RuleDescription ruleDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.SubscriptionDescription CreateSubscription(class Microsoft.ServiceBus.Messaging.SubscriptionDescription description, class Microsoft.ServiceBus.Messaging.RuleDescription ruleDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateSubscription(Microsoft.ServiceBus.Messaging.SubscriptionDescription,Microsoft.ServiceBus.Messaging.RuleDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateSubscription : Microsoft.ServiceBus.Messaging.SubscriptionDescription * Microsoft.ServiceBus.Messaging.RuleDescription -&gt; Microsoft.ServiceBus.Messaging.SubscriptionDescription" Usage="namespaceManager.CreateSubscription (description, ruleDescription)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.SubscriptionDescription" />
        <Parameter Name="ruleDescription" Type="Microsoft.ServiceBus.Messaging.RuleDescription" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="b9b6b-263">Ein <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> -Objekt, beschreibt die Attribute, mit denen das neue Abonnement erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-263">A <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> object describing the attributes with which the new subscription will be created.</span></span></param>
        <param name="ruleDescription"><span data-ttu-id="b9b6b-264">Ein <see cref="T:Microsoft.ServiceBus.Messaging.RuleDescription" /> -Objekt, das die Attribute, die Nachrichten werden mit dem abgeglichen und Reaktionen bewirkten, beschreibt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-264">A <see cref="T:Microsoft.ServiceBus.Messaging.RuleDescription" /> object describing the attributes with which the messages are matched and acted upon.</span></span></param>
        <summary><span data-ttu-id="b9b6b-265">Erstellt ein neues Abonnement im Dienstnamespace mit dem angegebenen abonnementbeschreibung und die Regelbeschreibung an.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-265">Creates a new subscription in the service namespace with the specified subscription description and rule description.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-266">Die <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> des neu erstellten Abonnements.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-266">The <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> of the newly created subscription.</span></span></returns>
        <remarks> <span data-ttu-id="b9b6b-267">Eine Standardregel erstellt, die mit Daten aus <paramref name="ruleDescription" />.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-267">A default rule will be created using data from <paramref name="ruleDescription" />.</span></span>
            <span data-ttu-id="b9b6b-268">Wenn <see cref="P:Microsoft.ServiceBus.Messaging.RuleDescription.Name" /> ist Null oder ein Leerzeichen, und klicken Sie dann der Namen der Regel erstellt werden <see cref="F:Microsoft.ServiceBus.Messaging.RuleDescription.DefaultRuleName" />.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-268">If <see cref="P:Microsoft.ServiceBus.Messaging.RuleDescription.Name" /> is null or white space, then the name of the rule created will be <see cref="F:Microsoft.ServiceBus.Messaging.RuleDescription.DefaultRuleName" />.</span></span> </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSubscription">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.SubscriptionDescription CreateSubscription (string topicPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.SubscriptionDescription CreateSubscription(string topicPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateSubscription(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateSubscription (topicPath As String, name As String) As SubscriptionDescription" />
      <MemberSignature Language="F#" Value="member this.CreateSubscription : string * string -&gt; Microsoft.ServiceBus.Messaging.SubscriptionDescription" Usage="namespaceManager.CreateSubscription (topicPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath"><span data-ttu-id="b9b6b-269">Der Themenname relativ zur Basisadresse Diensts-Namespace.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-269">The topic path relative to the service namespace base address.</span></span></param>
        <param name="name"><span data-ttu-id="b9b6b-270">Der Name des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-270">The name of the subscription.</span></span></param>
        <summary><span data-ttu-id="b9b6b-271">Erstellt ein neues Abonnement im Dienstnamespace mit dem angegebenen Thema Pfad und Abonnement an.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-271">Creates a new subscription in the service namespace with the specified topic path and subscription name.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-272">Die <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> des neu erstellten Abonnements.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-272">The <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> of the newly created subscription.</span></span></returns>
        <remarks> <span data-ttu-id="b9b6b-273">Standardmäßig wird ein Filter "Pass-Through" für dieses Abonnement erstellt dies, dass er alle Nachrichten bedeutet zu diesem Abonnement gesendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-273">Be default, A "pass-through" filter is created for this subscription, which means it will allow all message to go to this subscription.</span></span> <span data-ttu-id="b9b6b-274">Der Name des Filters ist <see cref="F:Microsoft.ServiceBus.Messaging.RuleDescription.DefaultRuleName" />.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-274">The name of the filter is <see cref="F:Microsoft.ServiceBus.Messaging.RuleDescription.DefaultRuleName" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSubscription">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.SubscriptionDescription CreateSubscription (string topicPath, string name, Microsoft.ServiceBus.Messaging.Filter filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.SubscriptionDescription CreateSubscription(string topicPath, string name, class Microsoft.ServiceBus.Messaging.Filter filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateSubscription(System.String,System.String,Microsoft.ServiceBus.Messaging.Filter)" />
      <MemberSignature Language="F#" Value="member this.CreateSubscription : string * string * Microsoft.ServiceBus.Messaging.Filter -&gt; Microsoft.ServiceBus.Messaging.SubscriptionDescription" Usage="namespaceManager.CreateSubscription (topicPath, name, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="filter" Type="Microsoft.ServiceBus.Messaging.Filter" />
      </Parameters>
      <Docs>
        <param name="topicPath"><span data-ttu-id="b9b6b-275">Der Themenname relativ zur Basisadresse Diensts-Namespace.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-275">The topic path relative to the service namespace base address.</span></span></param>
        <param name="name"><span data-ttu-id="b9b6b-276">Der Name des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-276">The name of the subscription.</span></span></param>
        <param name="filter"><span data-ttu-id="b9b6b-277">Der Filterausdruck, der zur Erfassung von Nachrichten, die den Filterwert Ausdruck erfüllen.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-277">The filter expression used to capture messages satisfying the filtering expression value.</span></span></param>
        <summary><span data-ttu-id="b9b6b-278">Erstellt ein neues Abonnement im Dienstnamespace mit dem angegebenen themenpfad, den Abonnementnamen und den Filterausdruck an.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-278">Creates a new subscription in the service namespace with the specified topic path, subscription name, and filter expression.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-279">Die <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> des neu erstellten Abonnements.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-279">The <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> of the newly created subscription.</span></span></returns>
        <remarks> <span data-ttu-id="b9b6b-280">Eine Standardregel erstellt, die mit Daten aus <paramref name="filter" /> und als benannte <see cref="F:Microsoft.ServiceBus.Messaging.RuleDescription.DefaultRuleName" />.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-280">A default rule will be created using data from <paramref name="filter" /> and named as <see cref="F:Microsoft.ServiceBus.Messaging.RuleDescription.DefaultRuleName" />.</span></span> </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSubscription">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.SubscriptionDescription CreateSubscription (string topicPath, string name, Microsoft.ServiceBus.Messaging.RuleDescription ruleDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.SubscriptionDescription CreateSubscription(string topicPath, string name, class Microsoft.ServiceBus.Messaging.RuleDescription ruleDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateSubscription(System.String,System.String,Microsoft.ServiceBus.Messaging.RuleDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateSubscription : string * string * Microsoft.ServiceBus.Messaging.RuleDescription -&gt; Microsoft.ServiceBus.Messaging.SubscriptionDescription" Usage="namespaceManager.CreateSubscription (topicPath, name, ruleDescription)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="ruleDescription" Type="Microsoft.ServiceBus.Messaging.RuleDescription" />
      </Parameters>
      <Docs>
        <param name="topicPath"><span data-ttu-id="b9b6b-281">Der Themenname relativ zur Basisadresse Diensts-Namespace.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-281">The topic path relative to the service namespace base address.</span></span></param>
        <param name="name"><span data-ttu-id="b9b6b-282">Der Name des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-282">The name of the subscription.</span></span></param>
        <param name="ruleDescription"><span data-ttu-id="b9b6b-283">Ein <see cref="T:Microsoft.ServiceBus.Messaging.RuleDescription" /> -Objekt, das die Attribute, die Nachrichten werden mit dem abgeglichen und Reaktionen bewirkten, beschreibt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-283">A <see cref="T:Microsoft.ServiceBus.Messaging.RuleDescription" /> object describing the attributes with which the messages are matched and acted upon.</span></span></param>
        <summary><span data-ttu-id="b9b6b-284">Erstellt ein neues Abonnement im Dienstnamespace mit der angegebenen themenpfad, Abonnementnamen und Regelbeschreibung an.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-284">Creates a new subscription in the service namespace with the specified topic path, subscription name, and rule description.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-285">Die <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> des neu erstellten Abonnements.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-285">The <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> of the newly created subscription.</span></span></returns>
        <remarks> <span data-ttu-id="b9b6b-286">Eine Standardregel erstellt, die mit Daten aus <paramref name="ruleDescription" />.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-286">A default rule will be created using data from <paramref name="ruleDescription" />.</span></span>
            <span data-ttu-id="b9b6b-287">Wenn <see cref="P:Microsoft.ServiceBus.Messaging.RuleDescription.Name" /> ist Null oder ein Leerzeichen, und klicken Sie dann der Namen der Regel erstellt werden <see cref="F:Microsoft.ServiceBus.Messaging.RuleDescription.DefaultRuleName" />.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-287">If <see cref="P:Microsoft.ServiceBus.Messaging.RuleDescription.Name" /> is null or white space, then the name of the rule created will be <see cref="F:Microsoft.ServiceBus.Messaging.RuleDescription.DefaultRuleName" />.</span></span> </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSubscriptionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; CreateSubscriptionAsync (Microsoft.ServiceBus.Messaging.SubscriptionDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; CreateSubscriptionAsync(class Microsoft.ServiceBus.Messaging.SubscriptionDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateSubscriptionAsync(Microsoft.ServiceBus.Messaging.SubscriptionDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateSubscriptionAsync (description As SubscriptionDescription) As Task(Of SubscriptionDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateSubscriptionAsync : Microsoft.ServiceBus.Messaging.SubscriptionDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;" Usage="namespaceManager.CreateSubscriptionAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.SubscriptionDescription" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="b9b6b-288">Ein <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> -Objekt, beschreibt die Attribute, mit denen das neue Abonnement erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-288">A <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> object describing the attributes with which the new subscription will be created.</span></span></param>
        <summary><span data-ttu-id="b9b6b-289">Erstellt asynchron ein neues Abonnement im Dienstnamespace mit der Beschreibung angegebenen Abonnement.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-289">Asynchronously creates a new subscription in the service namespace with the specified subscription description.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-290">Die asynchron erstellte Abonnement.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-290">The asynchronously created subscription.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSubscriptionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; CreateSubscriptionAsync (Microsoft.ServiceBus.Messaging.SubscriptionDescription description, Microsoft.ServiceBus.Messaging.Filter filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; CreateSubscriptionAsync(class Microsoft.ServiceBus.Messaging.SubscriptionDescription description, class Microsoft.ServiceBus.Messaging.Filter filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateSubscriptionAsync(Microsoft.ServiceBus.Messaging.SubscriptionDescription,Microsoft.ServiceBus.Messaging.Filter)" />
      <MemberSignature Language="F#" Value="member this.CreateSubscriptionAsync : Microsoft.ServiceBus.Messaging.SubscriptionDescription * Microsoft.ServiceBus.Messaging.Filter -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;" Usage="namespaceManager.CreateSubscriptionAsync (description, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.SubscriptionDescription" />
        <Parameter Name="filter" Type="Microsoft.ServiceBus.Messaging.Filter" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="b9b6b-291">Ein <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> -Objekt, beschreibt die Attribute, mit denen das neue Abonnement erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-291">A <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> object describing the attributes with which the new subscription will be created.</span></span></param>
        <param name="filter"><span data-ttu-id="b9b6b-292">Der Filterausdruck, der zur Erfassung von Nachrichten, die den Filterwert Ausdruck erfüllen.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-292">The filter expression used to capture messages satisfying the filtering expression value.</span></span></param>
        <summary><span data-ttu-id="b9b6b-293">Erstellt asynchron ein neues Abonnement im Dienstnamespace mit dem angegebenen abonnementbeschreibung und den Filterausdruck an.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-293">Asynchronously creates a new subscription in the service namespace with the specified subscription description and filter expression.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-294">Die asynchron erstellte Abonnement.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-294">The asynchronously created subscription.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSubscriptionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; CreateSubscriptionAsync (Microsoft.ServiceBus.Messaging.SubscriptionDescription description, Microsoft.ServiceBus.Messaging.RuleDescription ruleDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; CreateSubscriptionAsync(class Microsoft.ServiceBus.Messaging.SubscriptionDescription description, class Microsoft.ServiceBus.Messaging.RuleDescription ruleDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateSubscriptionAsync(Microsoft.ServiceBus.Messaging.SubscriptionDescription,Microsoft.ServiceBus.Messaging.RuleDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateSubscriptionAsync : Microsoft.ServiceBus.Messaging.SubscriptionDescription * Microsoft.ServiceBus.Messaging.RuleDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;" Usage="namespaceManager.CreateSubscriptionAsync (description, ruleDescription)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.SubscriptionDescription" />
        <Parameter Name="ruleDescription" Type="Microsoft.ServiceBus.Messaging.RuleDescription" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="b9b6b-295">Ein <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> -Objekt, beschreibt die Attribute, mit denen das neue Abonnement erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-295">A <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> object describing the attributes with which the new subscription will be created.</span></span></param>
        <param name="ruleDescription"><span data-ttu-id="b9b6b-296">Ein <see cref="T:Microsoft.ServiceBus.Messaging.RuleDescription" /> -Objekt, das die Attribute, die Nachrichten werden mit dem abgeglichen und Reaktionen bewirkten, beschreibt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-296">A <see cref="T:Microsoft.ServiceBus.Messaging.RuleDescription" /> object describing the attributes with which the messages are matched and acted upon.</span></span></param>
        <summary><span data-ttu-id="b9b6b-297">Erstellt asynchron ein neues Abonnement im Dienstnamespace mit dem angegebenen abonnementbeschreibung und die Regelbeschreibung ein.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-297">Asynchronously creates a new subscription in the service namespace with the specified subscription description and rule description.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-298">Die asynchron erstellte Abonnement.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-298">The asynchronously created subscription.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSubscriptionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; CreateSubscriptionAsync (string topicPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; CreateSubscriptionAsync(string topicPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateSubscriptionAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateSubscriptionAsync (topicPath As String, name As String) As Task(Of SubscriptionDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateSubscriptionAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;" Usage="namespaceManager.CreateSubscriptionAsync (topicPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath"><span data-ttu-id="b9b6b-299">Der Themenname relativ zur Basisadresse Diensts-Namespace.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-299">The topic path relative to the service namespace base address.</span></span></param>
        <param name="name"><span data-ttu-id="b9b6b-300">Der Name des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-300">The name of the subscription.</span></span></param>
        <summary><span data-ttu-id="b9b6b-301">Erstellt asynchron ein neues Abonnement im Dienstnamespace mit dem angegebenen Thema Pfad und Abonnement an.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-301">Asynchronously creates a new subscription in the service namespace with the specified topic path and subscription name.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-302">Die asynchron erstellte Abonnement.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-302">The asynchronously created subscription.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSubscriptionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; CreateSubscriptionAsync (string topicPath, string name, Microsoft.ServiceBus.Messaging.Filter filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; CreateSubscriptionAsync(string topicPath, string name, class Microsoft.ServiceBus.Messaging.Filter filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateSubscriptionAsync(System.String,System.String,Microsoft.ServiceBus.Messaging.Filter)" />
      <MemberSignature Language="F#" Value="member this.CreateSubscriptionAsync : string * string * Microsoft.ServiceBus.Messaging.Filter -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;" Usage="namespaceManager.CreateSubscriptionAsync (topicPath, name, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="filter" Type="Microsoft.ServiceBus.Messaging.Filter" />
      </Parameters>
      <Docs>
        <param name="topicPath"><span data-ttu-id="b9b6b-303">Der Themenname relativ zur Basisadresse Diensts-Namespace.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-303">The topic path relative to the service namespace base address.</span></span></param>
        <param name="name"><span data-ttu-id="b9b6b-304">Der Name des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-304">The name of the subscription.</span></span></param>
        <param name="filter"><span data-ttu-id="b9b6b-305">Der Filterausdruck, der zur Erfassung von Nachrichten, die den Filterwert Ausdruck erfüllen.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-305">The filter expression used to capture messages satisfying the filtering expression value.</span></span></param>
        <summary><span data-ttu-id="b9b6b-306">Erstellt asynchron ein neues Abonnement im Dienstnamespace mit der angegebenen themenpfad, Abonnementnamen und Filter-Ausdruck ein.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-306">Asynchronously creates a new subscription in the service namespace with the specified topic path, subscription name, and filter expression.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-307">Die asynchron erstellte Abonnement.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-307">The asynchronously created subscription.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSubscriptionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; CreateSubscriptionAsync (string topicPath, string name, Microsoft.ServiceBus.Messaging.RuleDescription ruleDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; CreateSubscriptionAsync(string topicPath, string name, class Microsoft.ServiceBus.Messaging.RuleDescription ruleDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateSubscriptionAsync(System.String,System.String,Microsoft.ServiceBus.Messaging.RuleDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateSubscriptionAsync : string * string * Microsoft.ServiceBus.Messaging.RuleDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;" Usage="namespaceManager.CreateSubscriptionAsync (topicPath, name, ruleDescription)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="ruleDescription" Type="Microsoft.ServiceBus.Messaging.RuleDescription" />
      </Parameters>
      <Docs>
        <param name="topicPath"><span data-ttu-id="b9b6b-308">Der Themenname relativ zur Basisadresse Diensts-Namespace.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-308">The topic path relative to the service namespace base address.</span></span></param>
        <param name="name"><span data-ttu-id="b9b6b-309">Der Name des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-309">The name of the subscription.</span></span></param>
        <param name="ruleDescription"><span data-ttu-id="b9b6b-310">Ein <see cref="T:Microsoft.ServiceBus.Messaging.RuleDescription" /> -Objekt, das die Attribute, die Nachrichten werden mit dem abgeglichen und Reaktionen bewirkten, beschreibt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-310">A <see cref="T:Microsoft.ServiceBus.Messaging.RuleDescription" /> object describing the attributes with which the messages are matched and acted upon.</span></span></param>
        <summary><span data-ttu-id="b9b6b-311">Erstellt asynchron ein neues Abonnement im Dienstnamespace mit der angegebenen themenpfad, Abonnementnamen und Regelbeschreibung ein.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-311">Asynchronously creates a new subscription in the service namespace with the specified topic path, subscription name, and rule description.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-312">Die asynchron erstellte Abonnement.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-312">The asynchronously created subscription.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateTopic">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.TopicDescription CreateTopic (Microsoft.ServiceBus.Messaging.TopicDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.TopicDescription CreateTopic(class Microsoft.ServiceBus.Messaging.TopicDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateTopic(Microsoft.ServiceBus.Messaging.TopicDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateTopic (description As TopicDescription) As TopicDescription" />
      <MemberSignature Language="F#" Value="member this.CreateTopic : Microsoft.ServiceBus.Messaging.TopicDescription -&gt; Microsoft.ServiceBus.Messaging.TopicDescription" Usage="namespaceManager.CreateTopic description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TopicDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.TopicDescription" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="b9b6b-313">Ein <see cref="T:Microsoft.ServiceBus.Messaging.TopicDescription" /> -Objekt, beschreibt die Attribute, mit denen das neue Thema erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-313">A <see cref="T:Microsoft.ServiceBus.Messaging.TopicDescription" /> object describing the attributes with which the new topic will be created.</span></span></param>
        <summary><span data-ttu-id="b9b6b-314">Erstellt ein neues Thema innerhalb des Dienstnamespace mit der Beschreibung angegebene Thema an.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-314">Creates a new topic inside the service namespace with the specified topic description.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-315">Die <see cref="T:Microsoft.ServiceBus.Messaging.TopicDescription" /> des neu erstellten Themas.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-315">The <see cref="T:Microsoft.ServiceBus.Messaging.TopicDescription" /> of the newly created topic.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateTopic">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.TopicDescription CreateTopic (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.TopicDescription CreateTopic(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateTopic(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateTopic (path As String) As TopicDescription" />
      <MemberSignature Language="F#" Value="member this.CreateTopic : string -&gt; Microsoft.ServiceBus.Messaging.TopicDescription" Usage="namespaceManager.CreateTopic path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TopicDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="b9b6b-316">Der Pfad des Themas relativ zur Basisadresse Diensts-Namespace.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-316">The path of the topic relative to the service namespace base address.</span></span></param>
        <summary><span data-ttu-id="b9b6b-317">Erstellt ein neues Thema innerhalb des Dienstnamespace mit den angegebenen Namespace Dienstpfad an.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-317">Creates a new topic inside the service namespace with the given service namespace path.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-318">Die <see cref="T:Microsoft.ServiceBus.Messaging.TopicDescription" /> des neu erstellten Themas.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-318">The <see cref="T:Microsoft.ServiceBus.Messaging.TopicDescription" /> of the newly created topic.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="b9b6b-319"><paramref name="path" />ist null oder leer ist, oder <paramref name="path" /> beginnt oder endet mit "/".</span><span class="sxs-lookup"><span data-stu-id="b9b6b-319"><paramref name="path" /> is null or empty, or <paramref name="path" /> begins or ends with “/”.</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="b9b6b-320">Länge des <paramref name="path" /> ist größer als <see cref="F:Microsoft.ServiceBus.Messaging.Constants.QueueNameMaximumLength" />.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-320">Length of <paramref name="path" /> is greater than <see cref="F:Microsoft.ServiceBus.Messaging.Constants.QueueNameMaximumLength" />.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="b9b6b-321">Timeout des Vorgangs. Das Zeitlimit wird initialisiert, durch die <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> Klasse.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-321">The operation times out. The timeout period is initialized through the <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> class.</span></span> <span data-ttu-id="b9b6b-322">Sie müssen möglicherweise den Wert erhöhen die <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" /> Eigenschaft, um diese Ausnahme zu vermeiden, wenn der Timeoutwert relativ gering ist.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-322">You may need to increase the value of the <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" /> property to avoid this exception if the timeout value is relatively low.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityAlreadyExistsException"><span data-ttu-id="b9b6b-323">Unter desselben Namespace befindet sich eine Warteschlange oder ein Thema mit dem gleichen Namen und Pfad.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-323">A queue or a topic with the same name and path exists under the same service namespace.</span></span></exception>
        <exception cref="T:System.UnauthorizedAccessException"><span data-ttu-id="b9b6b-324">Die <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> Objekt verfügt nicht über ausreichende Berechtigungen zum Ausführen dieses Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-324">The <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> object does not have sufficient permission to perform this operation.</span></span> <span data-ttu-id="b9b6b-325">Sie sollten prüfen, um sicherzustellen, dass Ihre <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> verfügt über den richtigen <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.TokenProvider" /> Anmeldeinformationen zum Ausführen dieses Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-325">You should check to ensure that your <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> has the correct <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.TokenProvider" /> credentials to perform this operation.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.QuotaExceededException"><span data-ttu-id="b9b6b-326">Die angegebene Größe in der Beschreibung wird nicht unterstützt oder die maximale zulässige Kontingent erreicht haben.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-326">Either the specified size in the description is not supported or the maximum allowable quota has been reached.</span></span> <span data-ttu-id="b9b6b-327">Sie müssen Geben Sie einen der unterstützten Größenwerte, löschen vorhandene Entitäten oder Ihr Kontingent vergrößern.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-327">You must specify one of the supported size values, delete existing entities, or increase your quota size.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException"><span data-ttu-id="b9b6b-328">Ein interner Fehler oder unerwartete Ausnahme auftritt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-328">An internal error or unexpected exception occurs.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CreateTopicAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt; CreateTopicAsync (Microsoft.ServiceBus.Messaging.TopicDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.TopicDescription&gt; CreateTopicAsync(class Microsoft.ServiceBus.Messaging.TopicDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateTopicAsync(Microsoft.ServiceBus.Messaging.TopicDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateTopicAsync (description As TopicDescription) As Task(Of TopicDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateTopicAsync : Microsoft.ServiceBus.Messaging.TopicDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;" Usage="namespaceManager.CreateTopicAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.TopicDescription" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="b9b6b-329">Ein <see cref="T:Microsoft.ServiceBus.Messaging.TopicDescription" /> -Objekt, beschreibt die Attribute, mit denen das neue Thema erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-329">A <see cref="T:Microsoft.ServiceBus.Messaging.TopicDescription" /> object describing the attributes with which the new topic will be created.</span></span></param>
        <summary><span data-ttu-id="b9b6b-330">Erstellt asynchron in den Dienstnamespace ein neues Thema mit der Beschreibung angegebene Thema ein.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-330">Asynchronously creates a new topic inside the service namespace with the specified topic description.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-331">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-331">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateTopicAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt; CreateTopicAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.TopicDescription&gt; CreateTopicAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateTopicAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateTopicAsync (path As String) As Task(Of TopicDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateTopicAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;" Usage="namespaceManager.CreateTopicAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="b9b6b-332">Der Pfad des Themas relativ zur Basisadresse Diensts-Namespace.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-332">The path of the topic relative to the service namespace base address.</span></span></param>
        <summary><span data-ttu-id="b9b6b-333">Erstellt asynchron in den Dienstnamespace ein neues Thema mit den angegebenen Namespace Dienstpfad an.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-333">Asynchronously creates a new topic inside the service namespace with the given service namespace path.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-334">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-334">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteConsumerGroup">
      <MemberSignature Language="C#" Value="public void DeleteConsumerGroup (string eventHubPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteConsumerGroup(string eventHubPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.DeleteConsumerGroup(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteConsumerGroup (eventHubPath As String, name As String)" />
      <MemberSignature Language="F#" Value="member this.DeleteConsumerGroup : string * string -&gt; unit" Usage="namespaceManager.DeleteConsumerGroup (eventHubPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventHubPath"><span data-ttu-id="b9b6b-335">Der Pfad zu den Event Hub.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-335">The path to the Event Hub.</span></span></param>
        <param name="name"><span data-ttu-id="b9b6b-336">Der Name des zu löschenden consumergruppe.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-336">The name of the consumer group to delete.</span></span></param>
        <summary><span data-ttu-id="b9b6b-337">Löscht eine consumergruppe.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-337">Deletes a consumer group.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteConsumerGroupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteConsumerGroupAsync (string eventHubPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteConsumerGroupAsync(string eventHubPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.DeleteConsumerGroupAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteConsumerGroupAsync (eventHubPath As String, name As String) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteConsumerGroupAsync : string * string -&gt; System.Threading.Tasks.Task" Usage="namespaceManager.DeleteConsumerGroupAsync (eventHubPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventHubPath"><span data-ttu-id="b9b6b-338">Der Pfad zu den Event Hub.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-338">The path to the Event Hub.</span></span></param>
        <param name="name"><span data-ttu-id="b9b6b-339">Der Name des zu löschenden consumergruppe.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-339">The name of the consumer group to delete.</span></span></param>
        <summary><span data-ttu-id="b9b6b-340">Löscht asynchron eine consumergruppe.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-340">Asynchronously deletes a consumer group.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-341">Die Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-341">The task that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteEventHub">
      <MemberSignature Language="C#" Value="public void DeleteEventHub (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteEventHub(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.DeleteEventHub(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteEventHub (path As String)" />
      <MemberSignature Language="F#" Value="member this.DeleteEventHub : string -&gt; unit" Usage="namespaceManager.DeleteEventHub path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="b9b6b-342">Der Pfad zu den Event Hub.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-342">The path to the Event Hub.</span></span></param>
        <summary><span data-ttu-id="b9b6b-343">Löscht einen Event Hub.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-343">Deletes an Event Hub.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteEventHubAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteEventHubAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteEventHubAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.DeleteEventHubAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteEventHubAsync (path As String) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteEventHubAsync : string -&gt; System.Threading.Tasks.Task" Usage="namespaceManager.DeleteEventHubAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="b9b6b-344">Der Pfad zu den Event Hub.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-344">The path to the Event Hub.</span></span></param>
        <summary><span data-ttu-id="b9b6b-345">Löscht asynchron einen Event Hub.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-345">Asynchronously deletes an Event Hub.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-346">Die Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-346">The task that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteQueue">
      <MemberSignature Language="C#" Value="public void DeleteQueue (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteQueue(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.DeleteQueue(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteQueue (path As String)" />
      <MemberSignature Language="F#" Value="member this.DeleteQueue : string -&gt; unit" Usage="namespaceManager.DeleteQueue path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="b9b6b-347">Der Pfad der Warteschlange relativ zur Basisadresse Diensts-Namespace.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-347">The path of the queue relative to the service namespace base address.</span></span></param>
        <summary><span data-ttu-id="b9b6b-348">Löscht die Warteschlange, die durch den Pfad relativ zur Basisadresse Diensts-Namespace beschrieben.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-348">Deletes the queue described by the path relative to the service namespace base address.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="b9b6b-349"><paramref name="path" />ist leer oder null, oder <paramref name="path" /> beginnt oder endet mit "/".</span><span class="sxs-lookup"><span data-stu-id="b9b6b-349"><paramref name="path" /> is empty or null, or <paramref name="path" /> starts or ends with "/".</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="b9b6b-350">Die Länge des <paramref name="path" /> ist größer als <see cref="F:Microsoft.ServiceBus.Messaging.Constants.QueueNameMaximumLength" />.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-350">The length of <paramref name="path" /> is greater than <see cref="F:Microsoft.ServiceBus.Messaging.Constants.QueueNameMaximumLength" />.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="b9b6b-351">Timeout des Vorgangs. Das Zeitlimit wird initialisiert, durch die <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> Klasse.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-351">The operation times out. The timeout period is initialized through the <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> class.</span></span> <span data-ttu-id="b9b6b-352">Sie müssen möglicherweise den Wert erhöhen die <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" /> Eigenschaft, um diese Ausnahme zu vermeiden, wenn der Timeoutwert relativ gering ist.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-352">You may need to increase the value of the <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" /> property to avoid this exception if the timeout value is relatively low.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException"><span data-ttu-id="b9b6b-353">Warteschlange ist unter diesem Pfad nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-353">Queue does not exist under this path.</span></span></exception>
        <exception cref="T:System.UnauthorizedAccessException"><span data-ttu-id="b9b6b-354">Die <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> Objekt verfügt nicht über ausreichende Berechtigungen zum Ausführen dieses Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-354">The <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> object does not have sufficient permission to perform this operation.</span></span> <span data-ttu-id="b9b6b-355">Sie sollten prüfen, um sicherzustellen, dass Ihre <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> verfügt über den richtigen <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.TokenProvider" /> Anmeldeinformationen zum Ausführen dieses Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-355">You should check to ensure that your <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> has the correct <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.TokenProvider" /> credentials to perform this operation.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException"><span data-ttu-id="b9b6b-356">Ein interner Fehler oder unerwartete Ausnahme auftritt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-356">An internal error or unexpected exception occurs.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteQueueAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteQueueAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteQueueAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.DeleteQueueAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteQueueAsync (path As String) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteQueueAsync : string -&gt; System.Threading.Tasks.Task" Usage="namespaceManager.DeleteQueueAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="b9b6b-357">Der Pfad der Warteschlange relativ zur Basisadresse Diensts-Namespace.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-357">The path of the queue relative to the service namespace base address.</span></span></param>
        <summary><span data-ttu-id="b9b6b-358">Löscht asynchron die Warteschlange, die durch den Pfad relativ zur Basisadresse Diensts-Namespace beschrieben.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-358">Asynchronously deletes the queue described by the path relative to the service namespace base address.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-359">Der asynchrone Warteschlangenvorgang zum Löschen der.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-359">The asynchronous delete queue operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteRelay">
      <MemberSignature Language="C#" Value="public void DeleteRelay (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteRelay(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.DeleteRelay(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteRelay (path As String)" />
      <MemberSignature Language="F#" Value="member this.DeleteRelay : string -&gt; unit" Usage="namespaceManager.DeleteRelay path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="b9b6b-360">Der Pfad des Relays relativ zur Basisadresse Diensts-Namespace.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-360">The path of the relay relative to the service namespace base address.</span></span></param>
        <summary><span data-ttu-id="b9b6b-361">Löscht das Relay durch den Pfad relativ zur Basisadresse Diensts-Namespace beschrieben.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-361">Deletes the relay described by the path relative to the service namespace base address.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteRelayAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteRelayAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteRelayAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.DeleteRelayAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteRelayAsync (path As String) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteRelayAsync : string -&gt; System.Threading.Tasks.Task" Usage="namespaceManager.DeleteRelayAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="b9b6b-362">Der Pfad des Relays relativ zur Basisadresse Diensts-Namespace.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-362">The path of the relay relative to the service namespace base address.</span></span></param>
        <summary><span data-ttu-id="b9b6b-363">Löscht asynchron das Relay durch den Pfad relativ zur Basisadresse Diensts-Namespace beschrieben.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-363">Asynchronously deletes the relay described by the path relative to the service namespace base address.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-364">Der asynchrone Löschvorgang Relay.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-364">The asynchronous delete relay operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteSubscription">
      <MemberSignature Language="C#" Value="public void DeleteSubscription (string topicPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteSubscription(string topicPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.DeleteSubscription(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteSubscription (topicPath As String, name As String)" />
      <MemberSignature Language="F#" Value="member this.DeleteSubscription : string * string -&gt; unit" Usage="namespaceManager.DeleteSubscription (topicPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath"><span data-ttu-id="b9b6b-365">Der Themenname relativ zur Basisadresse Diensts-Namespace.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-365">The topic path relative to the service namespace base address.</span></span></param>
        <param name="name"><span data-ttu-id="b9b6b-366">Der Name des Abonnements zu löschen.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-366">The name of the subscription to delete.</span></span></param>
        <summary><span data-ttu-id="b9b6b-367">Löscht das Abonnement mit dem angegebenen Pfad und Abonnement Themanamen.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-367">Deletes the subscription with the specified topic path and subscription name.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteSubscriptionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteSubscriptionAsync (string topicPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteSubscriptionAsync(string topicPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.DeleteSubscriptionAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteSubscriptionAsync (topicPath As String, name As String) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteSubscriptionAsync : string * string -&gt; System.Threading.Tasks.Task" Usage="namespaceManager.DeleteSubscriptionAsync (topicPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath"><span data-ttu-id="b9b6b-368">Der Themenname relativ zur Basisadresse Diensts-Namespace.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-368">The topic path relative to the service namespace base address.</span></span></param>
        <param name="name"><span data-ttu-id="b9b6b-369">Der Name des Abonnements zu löschen.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-369">The name of the subscription to delete.</span></span></param>
        <summary><span data-ttu-id="b9b6b-370">Löscht asynchron das Abonnement mit dem angegebenen Pfad und Abonnement Themanamen.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-370">Asynchronously deletes the subscription with the specified topic path and subscription name.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-371">Der asynchrone Abonnementvorgang zum Löschen der.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-371">The asynchronous delete subscription operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteTopic">
      <MemberSignature Language="C#" Value="public void DeleteTopic (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteTopic(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.DeleteTopic(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteTopic (path As String)" />
      <MemberSignature Language="F#" Value="member this.DeleteTopic : string -&gt; unit" Usage="namespaceManager.DeleteTopic path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="b9b6b-372">Der Pfad des Themas relativ zur Basisadresse Diensts-Namespace.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-372">The path of the topic relative to the service namespace base address.</span></span></param>
        <summary><span data-ttu-id="b9b6b-373">Löscht das Thema, das durch den Pfad relativ zur Basisadresse Diensts-Namespace beschrieben.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-373">Deletes the topic described by path relative to the service namespace base address.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="b9b6b-374"><paramref name="path" />ist null oder leer ist, oder <paramref name="path" /> beginnt oder endet mit "/".</span><span class="sxs-lookup"><span data-stu-id="b9b6b-374"><paramref name="path" /> is null or empty, or <paramref name="path" /> starts or ends with "/".</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteTopicAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteTopicAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteTopicAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.DeleteTopicAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteTopicAsync (path As String) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteTopicAsync : string -&gt; System.Threading.Tasks.Task" Usage="namespaceManager.DeleteTopicAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="b9b6b-375">Der Pfad des Themas relativ zur Basisadresse Diensts-Namespace.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-375">The path of the topic relative to the service namespace base address.</span></span></param>
        <summary><span data-ttu-id="b9b6b-376">Löscht asynchron das Thema, das durch den Pfad relativ zur Basisadresse Diensts-Namespace beschrieben.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-376">Asynchronously deletes the topic described by path relative to the service namespace base address.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-377">Der Vorgang des asynchronen gelöschtes Thema.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-377">The asynchronous deleted topic operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventHubExists">
      <MemberSignature Language="C#" Value="public bool EventHubExists (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool EventHubExists(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.EventHubExists(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function EventHubExists (path As String) As Boolean" />
      <MemberSignature Language="F#" Value="member this.EventHubExists : string -&gt; bool" Usage="namespaceManager.EventHubExists path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="b9b6b-378">Der Pfad zu den Event Hub.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-378">The path to the Event Hub.</span></span></param>
        <summary><span data-ttu-id="b9b6b-379">Gibt an, und zwar unabhängig davon, ob ein Event Hub vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-379">Indicates whether or not an Event Hub exists.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-380">Gibt "true" zurück, wenn der Event Hub vorhanden ist; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="b9b6b-380">Returns true if the Event Hub exists; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventHubExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; EventHubExistsAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;bool&gt; EventHubExistsAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.EventHubExistsAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function EventHubExistsAsync (path As String) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EventHubExistsAsync : string -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="namespaceManager.EventHubExistsAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="b9b6b-381">Der Pfad des Event Hubs.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-381">The path of the event hub.</span></span></param>
        <summary><span data-ttu-id="b9b6b-382">Ermittelt asynchron, ob der Event Hub aus dem Dienstnamespace vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-382">Asynchronously determines whether the event hub exists from the service namespace.</span></span> </summary>
        <returns><span data-ttu-id="b9b6b-383">Die Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-383">The task representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetConsumerGroup">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.ConsumerGroupDescription GetConsumerGroup (string eventHubPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription GetConsumerGroup(string eventHubPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetConsumerGroup(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetConsumerGroup (eventHubPath As String, name As String) As ConsumerGroupDescription" />
      <MemberSignature Language="F#" Value="member this.GetConsumerGroup : string * string -&gt; Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" Usage="namespaceManager.GetConsumerGroup (eventHubPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.ConsumerGroupDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventHubPath"><span data-ttu-id="b9b6b-384">Der Pfad zu den Event Hub.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-384">The path to the Event Hub.</span></span></param>
        <param name="name"><span data-ttu-id="b9b6b-385">Der Name der Gruppe "Consumer".</span><span class="sxs-lookup"><span data-stu-id="b9b6b-385">The name of the consumer group.</span></span></param>
        <summary><span data-ttu-id="b9b6b-386">Ruft ein Event Hubs-Consumer-Gruppe ab.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-386">Gets an Event Hubs consumer group.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-387">Gibt <see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />zurück.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-387">Returns <see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetConsumerGroupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt; GetConsumerGroupAsync (string eventHubPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt; GetConsumerGroupAsync(string eventHubPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetConsumerGroupAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetConsumerGroupAsync (eventHubPath As String, name As String) As Task(Of ConsumerGroupDescription)" />
      <MemberSignature Language="F#" Value="member this.GetConsumerGroupAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;" Usage="namespaceManager.GetConsumerGroupAsync (eventHubPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventHubPath"><span data-ttu-id="b9b6b-388">Der Pfad zu den Event Hub.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-388">The path to the Event Hub.</span></span></param>
        <param name="name"><span data-ttu-id="b9b6b-389">Der Name der Gruppe "Consumer".</span><span class="sxs-lookup"><span data-stu-id="b9b6b-389">The name of the consumer group.</span></span></param>
        <summary><span data-ttu-id="b9b6b-390">Ruft asynchron eine consumergruppe ab.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-390">Asynchronously gets a consumer group.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-391">Die Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-391">The task representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetConsumerGroups">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt; GetConsumerGroups (string eventHubPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt; GetConsumerGroups(string eventHubPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetConsumerGroups(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetConsumerGroups (eventHubPath As String) As IEnumerable(Of ConsumerGroupDescription)" />
      <MemberSignature Language="F#" Value="member this.GetConsumerGroups : string -&gt; seq&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;" Usage="namespaceManager.GetConsumerGroups eventHubPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventHubPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventHubPath"><span data-ttu-id="b9b6b-392">Der Pfad zu den Event Hub.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-392">The path to the Event Hub.</span></span></param>
        <summary><span data-ttu-id="b9b6b-393">Ruft eine Auflistung, die einen Satz von consumergruppen darstellt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-393">Gets a collection representing a set of consumer groups.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-394">Gibt ein <see cref="T:System.Collections.Generic.IEnumerable`1" /> Objekt, das den Satz von consumergruppen darstellt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-394">Returns an <see cref="T:System.Collections.Generic.IEnumerable`1" /> object representing the set of consumer groups.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetConsumerGroupsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;&gt; GetConsumerGroupsAsync (string eventHubPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;&gt; GetConsumerGroupsAsync(string eventHubPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetConsumerGroupsAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetConsumerGroupsAsync (eventHubPath As String) As Task(Of IEnumerable(Of ConsumerGroupDescription))" />
      <MemberSignature Language="F#" Value="member this.GetConsumerGroupsAsync : string -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;&gt;" Usage="namespaceManager.GetConsumerGroupsAsync eventHubPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventHubPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventHubPath"><span data-ttu-id="b9b6b-395">Der Pfad zu den Event Hub.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-395">The path to the Event Hub.</span></span></param>
        <summary><span data-ttu-id="b9b6b-396">Ruft asynchron einen Satz von consumergruppen ab.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-396">Asynchronously gets a set of consumer groups.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-397">Die Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-397">The task representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEventHub">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventHubDescription GetEventHub (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventHubDescription GetEventHub(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetEventHub(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEventHub (path As String) As EventHubDescription" />
      <MemberSignature Language="F#" Value="member this.GetEventHub : string -&gt; Microsoft.ServiceBus.Messaging.EventHubDescription" Usage="namespaceManager.GetEventHub path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="b9b6b-398">Der Pfad zu den Event Hub.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-398">The path to the Event Hub.</span></span></param>
        <summary><span data-ttu-id="b9b6b-399">Ruft Informationen zu einem Event Hub ab.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-399">Gets information about an Event Hub.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-400">Gibt ein <see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" /> Objekt, das die Event Hub-Beschreibung enthält.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-400">Returns an <see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" /> object that contains the Event Hub description.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEventHubAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt; GetEventHubAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.EventHubDescription&gt; GetEventHubAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetEventHubAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEventHubAsync (path As String) As Task(Of EventHubDescription)" />
      <MemberSignature Language="F#" Value="member this.GetEventHubAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt;" Usage="namespaceManager.GetEventHubAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="b9b6b-401">Der Pfad zu den Event Hub.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-401">The path to the Event Hub.</span></span></param>
        <summary><span data-ttu-id="b9b6b-402">Ruft die Informationen zu einem Event Hub asynchron ab.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-402">Asynchronously gets information about an Event Hub.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-403">Die Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-403">The task representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEventHubPartition">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.PartitionDescription GetEventHubPartition (string eventHubPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.PartitionDescription GetEventHubPartition(string eventHubPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetEventHubPartition(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEventHubPartition (eventHubPath As String, name As String) As PartitionDescription" />
      <MemberSignature Language="F#" Value="member this.GetEventHubPartition : string * string -&gt; Microsoft.ServiceBus.Messaging.PartitionDescription" Usage="namespaceManager.GetEventHubPartition (eventHubPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.PartitionDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventHubPath"><span data-ttu-id="b9b6b-404">Der Pfad zu den Event Hub.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-404">The path to the Event Hub.</span></span></param>
        <param name="name"><span data-ttu-id="b9b6b-405">Die ID der Event Hub-Partition.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-405">The ID of the Event Hub partition.</span></span></param>
        <summary><span data-ttu-id="b9b6b-406">Gibt Informationen über die angegebene Event Hub-Partition zurück.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-406">Returns information about the specified Event Hub partition.</span></span> <span data-ttu-id="b9b6b-407">Diese Methode setzt voraus, sollen von Partitionsinformationen für die Partition, die gemäß der <paramref name="name" /> Parameter, der die standardconsumergruppe gehört verweist <paramref name="eventHubPath" />.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-407">This method assumes that you want partition information for the partition specified by the <paramref name="name" /> parameter that belongs to the default consumer group pointed to by <paramref name="eventHubPath" />.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-408">Gibt <see cref="T:Microsoft.ServiceBus.Messaging.PartitionDescription" />zurück.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-408">Returns <see cref="T:Microsoft.ServiceBus.Messaging.PartitionDescription" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEventHubPartition">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.PartitionDescription GetEventHubPartition (string eventHubPath, string consumerGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.PartitionDescription GetEventHubPartition(string eventHubPath, string consumerGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetEventHubPartition(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEventHubPartition (eventHubPath As String, consumerGroupName As String, name As String) As PartitionDescription" />
      <MemberSignature Language="F#" Value="member this.GetEventHubPartition : string * string * string -&gt; Microsoft.ServiceBus.Messaging.PartitionDescription" Usage="namespaceManager.GetEventHubPartition (eventHubPath, consumerGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.PartitionDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventHubPath"></param>
        <param name="consumerGroupName"></param>
        <param name="name"></param>
        <summary />
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEventHubPartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.PartitionDescription&gt; GetEventHubPartitionAsync (string eventHubPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.PartitionDescription&gt; GetEventHubPartitionAsync(string eventHubPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetEventHubPartitionAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEventHubPartitionAsync (eventHubPath As String, name As String) As Task(Of PartitionDescription)" />
      <MemberSignature Language="F#" Value="member this.GetEventHubPartitionAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.PartitionDescription&gt;" Usage="namespaceManager.GetEventHubPartitionAsync (eventHubPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.PartitionDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventHubPath"><span data-ttu-id="b9b6b-409">Der Pfad zu den Event Hub.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-409">The path to the Event Hub.</span></span></param>
        <param name="name"><span data-ttu-id="b9b6b-410">Die ID der Event Hub-Partition.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-410">The ID of the Event Hub partition.</span></span></param>
        <summary><span data-ttu-id="b9b6b-411">Asynchrone Version von <see cref="M:Microsoft.ServiceBus.NamespaceManager.GetEventHubPartition(System.String,System.String)" />.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-411">Asynchronous version of <see cref="M:Microsoft.ServiceBus.NamespaceManager.GetEventHubPartition(System.String,System.String)" />.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-412">Gibt <see cref="T:System.Threading.Tasks.Task`1" />zurück.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-412">Returns <see cref="T:System.Threading.Tasks.Task`1" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEventHubPartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.PartitionDescription&gt; GetEventHubPartitionAsync (string eventHubPath, string consumerGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.PartitionDescription&gt; GetEventHubPartitionAsync(string eventHubPath, string consumerGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetEventHubPartitionAsync(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEventHubPartitionAsync (eventHubPath As String, consumerGroupName As String, name As String) As Task(Of PartitionDescription)" />
      <MemberSignature Language="F#" Value="member this.GetEventHubPartitionAsync : string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.PartitionDescription&gt;" Usage="namespaceManager.GetEventHubPartitionAsync (eventHubPath, consumerGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.PartitionDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventHubPath"><span data-ttu-id="b9b6b-413">Der Pfad zu den Event Hub.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-413">The path to the Event Hub.</span></span></param>
        <param name="consumerGroupName"><span data-ttu-id="b9b6b-414">Der Name des Event Hubs-Consumer-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-414">The name of the Event Hubs consumer group.</span></span></param>
        <param name="name"><span data-ttu-id="b9b6b-415">Die ID der Partition Event Hubs.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-415">The ID of the Event Hubs partition.</span></span></param>
        <summary><span data-ttu-id="b9b6b-416">Asynchrone Version von <see cref="M:Microsoft.ServiceBus.NamespaceManager.GetEventHubPartition(System.String,System.String)" />.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-416">Asynchronous version of <see cref="M:Microsoft.ServiceBus.NamespaceManager.GetEventHubPartition(System.String,System.String)" />.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-417">Gibt <see cref="T:System.Threading.Tasks.Task`1" />zurück.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-417">Returns <see cref="T:System.Threading.Tasks.Task`1" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEventHubs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt; GetEventHubs ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.EventHubDescription&gt; GetEventHubs() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetEventHubs" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEventHubs () As IEnumerable(Of EventHubDescription)" />
      <MemberSignature Language="F#" Value="member this.GetEventHubs : unit -&gt; seq&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt;" Usage="namespaceManager.GetEventHubs " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="b9b6b-418">Ruft eine Auflistung, die einen Satz von Event Hubs darstellt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-418">Gets a collection representing a set of Event Hubs.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-419">Gibt ein <see cref="T:System.Collections.Generic.IEnumerable`1" /> Objekt, das den Satz von Event Hubs darstellt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-419">Returns an <see cref="T:System.Collections.Generic.IEnumerable`1" /> object representing the set of Event Hubs.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEventHubsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt;&gt; GetEventHubsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.EventHubDescription&gt;&gt; GetEventHubsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetEventHubsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEventHubsAsync () As Task(Of IEnumerable(Of EventHubDescription))" />
      <MemberSignature Language="F#" Value="member this.GetEventHubsAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt;&gt;" Usage="namespaceManager.GetEventHubsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="b9b6b-420">Ruft asynchron eine Liste von Event Hubs ab.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-420">Asynchronously gets a list of Event Hubs.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-421">Die Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-421">The task representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetQueue">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.QueueDescription GetQueue (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.QueueDescription GetQueue(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetQueue(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetQueue (path As String) As QueueDescription" />
      <MemberSignature Language="F#" Value="member this.GetQueue : string -&gt; Microsoft.ServiceBus.Messaging.QueueDescription" Usage="namespaceManager.GetQueue path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="b9b6b-422">Der Pfad der Warteschlange relativ zur Basisadresse Diensts-Namespace.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-422">The path of the queue relative to the service namespace base address.</span></span></param>
        <summary><span data-ttu-id="b9b6b-423">Ruft eine Warteschlange aus dem Dienstnamespace ab.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-423">Retrieves a queue from the service namespace.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-424">Ein <see cref="T:Microsoft.ServiceBus.Messaging.QueueDescription" /> handle für die Warteschlange oder ein <see cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException" /> -Ausnahme aus, wenn die Warteschlange im Dienstnamespace nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-424">A <see cref="T:Microsoft.ServiceBus.Messaging.QueueDescription" /> handle to the queue, or a <see cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException" /> exception if the queue does not exist in the service namespace.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="b9b6b-425"><paramref name="path" />ist leer oder null, oder <paramref name="path" /> beginnt oder endet mit "/".</span><span class="sxs-lookup"><span data-stu-id="b9b6b-425"><paramref name="path" /> is empty or null, or <paramref name="path" /> starts or ends with "/".</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="b9b6b-426">Timeout des Vorgangs. Das Zeitlimit wird initialisiert, durch die <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> Klasse.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-426">The operation times out. The timeout period is initialized through the <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> class.</span></span> <span data-ttu-id="b9b6b-427">Sie müssen möglicherweise den Wert erhöhen die <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" /> Eigenschaft, um diese Ausnahme zu vermeiden, wenn der Timeoutwert relativ gering ist.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-427">You may need to increase the value of the <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" /> property to avoid this exception if the timeout value is relatively low.</span></span></exception>
        <exception cref="T:System.UnauthorizedAccessException"><span data-ttu-id="b9b6b-428">Die <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> Objekt verfügt nicht über ausreichende Berechtigungen zum Ausführen dieses Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-428">The <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> object does not have sufficient permission to perform this operation.</span></span> <span data-ttu-id="b9b6b-429">Sie sollten prüfen, um sicherzustellen, dass Ihre <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> verfügt über den richtigen <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.TokenProvider" /> Anmeldeinformationen zum Ausführen dieses Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-429">You should check to ensure that your <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> has the correct <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.TokenProvider" /> credentials to perform this operation.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException"><span data-ttu-id="b9b6b-430">Die Warteschlange ist nicht im Dienstnamespace vorhanden.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-430">The queue does not exist in the service namespace.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException"><span data-ttu-id="b9b6b-431">Ein interner Fehler oder unerwartete Ausnahme auftritt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-431">An internal error or unexpected exception occurs.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetQueueAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt; GetQueueAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.QueueDescription&gt; GetQueueAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetQueueAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetQueueAsync (path As String) As Task(Of QueueDescription)" />
      <MemberSignature Language="F#" Value="member this.GetQueueAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;" Usage="namespaceManager.GetQueueAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="b9b6b-432">Der Pfad der Warteschlange relativ zur Basisadresse Diensts-Namespace.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-432">The path of the queue relative to the service namespace base address.</span></span></param>
        <summary><span data-ttu-id="b9b6b-433">Ruft asynchron eine Warteschlange Dienstnamespace ab.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-433">Asynchronously retrieves a queue from the service namespace.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-434">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-434">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetQueues">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt; GetQueues ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.QueueDescription&gt; GetQueues() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetQueues" />
      <MemberSignature Language="VB.NET" Value="Public Function GetQueues () As IEnumerable(Of QueueDescription)" />
      <MemberSignature Language="F#" Value="member this.GetQueues : unit -&gt; seq&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;" Usage="namespaceManager.GetQueues " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="b9b6b-435">Ruft eine aufzählbare Auflistung von alle Warteschlangen im Dienstnamespace ab.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-435">Retrieves an enumerable collection of all queues in the service namespace.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-436">Ein <see cref="T:System.Collections.Generic.IEnumerable`1" /> -Objekt, das die Auflistung aller Warteschlangen in der Service-Namespace oder eine leere Auflistung zurück, wenn keine Warteschlange vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-436">An <see cref="T:System.Collections.Generic.IEnumerable`1" /> object that represents the collection of all queues in the service namespace or returns an empty collection if no queue exists.</span></span> </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="b9b6b-437">Timeout des Vorgangs. Das Zeitlimit wird initialisiert, durch die <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> Klasse.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-437">The operation times out. The timeout period is initialized through the <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> class.</span></span> <span data-ttu-id="b9b6b-438">Sie müssen möglicherweise den Wert erhöhen die <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" /> Eigenschaft, um diese Ausnahme zu vermeiden, wenn der Timeoutwert relativ gering ist.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-438">You may need to increase the value of the <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" /> property to avoid this exception if the timeout value is relatively low.</span></span></exception>
        <exception cref="T:System.UnauthorizedAccessException"><span data-ttu-id="b9b6b-439">Die <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> Objekt verfügt nicht über ausreichende Berechtigungen zum Ausführen dieses Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-439">The <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> object does not have sufficient permission to perform this operation.</span></span> <span data-ttu-id="b9b6b-440">Sie sollten prüfen, um sicherzustellen, dass Ihre <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> verfügt über den richtigen <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.TokenProvider" /> Anmeldeinformationen zum Ausführen dieses Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-440">You should check to ensure that your <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> has the correct <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.TokenProvider" /> credentials to perform this operation.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException"><span data-ttu-id="b9b6b-441">Ein interner Fehler oder unerwartete Ausnahme auftritt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-441">An internal error or unexpected exception occurs.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetQueues">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt; GetQueues (string filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.QueueDescription&gt; GetQueues(string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetQueues(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetQueues (filter As String) As IEnumerable(Of QueueDescription)" />
      <MemberSignature Language="F#" Value="member this.GetQueues : string -&gt; seq&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;" Usage="namespaceManager.GetQueues filter" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="filter"><span data-ttu-id="b9b6b-442">Eine Zeichenfolge, die zum Filtern der Warteschlangen abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-442">A string used to filter the queues to be retrieved.</span></span></param>
        <summary><span data-ttu-id="b9b6b-443">Ruft eine aufzählbare Auflistung von alle Warteschlangen im Dienstnamespace mit dem angegebenen Filter ab.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-443">Retrieves an enumerable collection of all queues in the service namespace with the specified filter.</span></span> <span data-ttu-id="b9b6b-444">Sie können durch eine Kombination von Entitätsname (einschließlich beginnt mit), Entität Länge (Gt oder Lt), erstellt, aktualisiert und Zugriffs-Zeit (Gt oder Lt) filtern.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-444">You can filter by a combination of entity name (including starts with), entity length (Gt or Lt), created, updated, and accessed time (Gt or Lt).</span></span></summary>
        <returns><span data-ttu-id="b9b6b-445">Ein <see cref="T:System.Collections.Generic.IEnumerable`1" /> -Objekt, das die Auflistung aller Warteschlangen in der Service-Namespace oder eine leere Auflistung zurück, wenn keine Warteschlange vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-445">An <see cref="T:System.Collections.Generic.IEnumerable`1" /> object that represents the collection of all queues in the service namespace or returns an empty collection if no queue exists.</span></span></returns>
        <remarks>
            <span data-ttu-id="b9b6b-446">Filtern von ausdrucksformaten: {aus} {logischer Operator} {Value} und {Filterausdruck} {Funktion} {logischer Operator} {Value} und {Filterausdruck}</span><span class="sxs-lookup"><span data-stu-id="b9b6b-446">Filter expression formats:  {Propery} {Logical Operator} {Value} AND {Filter expression} {Function} {Logical Operator} {Value} AND {Filter expression}</span></span>
                                        -----------------------------------------------------------------------------------------
            <span data-ttu-id="b9b6b-447">Verfügbare Eigenschaften: Pfad | ModifiedAt | AccessedAt | CreatedAt | MessageCount logische Operatoren: Eq | Ne | Gt | Ge | Lt | LE</span><span class="sxs-lookup"><span data-stu-id="b9b6b-447">Available properties:       Path | ModifiedAt | AccessedAt | CreatedAt | MessageCount Logical operators:          Eq | Ne | Gt | Ge | Lt | Le</span></span>  
            <span data-ttu-id="b9b6b-448">Wert: Geben Sie ein Wert der entsprechenden Eigenschaft Funktionen: "StartsWith" ({aus}, {Value})</span><span class="sxs-lookup"><span data-stu-id="b9b6b-448">Value:                      A value of the corresponding property type Functions:                  startswith({Propery}, {Value})</span></span>
            </remarks>
        <example>
          <code>
            <span data-ttu-id="b9b6b-449">Var QueuesWithMessages = namespaceManager.GetQueues ("MessageCount Gt 0"); Var QueuesStartsWith = namespaceManager.GetQueues ($"" StartsWith "(Pfad,"Queue") Eq" true "");</span><span class="sxs-lookup"><span data-stu-id="b9b6b-449">var queuesWithMessages = namespaceManager.GetQueues("messageCount Gt 0"); var queuesStartsWith = namespaceManager.GetQueues($"startswith(path, 'queue') eq true");</span></span>
            </code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="GetQueuesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;&gt; GetQueuesAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.QueueDescription&gt;&gt; GetQueuesAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetQueuesAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetQueuesAsync () As Task(Of IEnumerable(Of QueueDescription))" />
      <MemberSignature Language="F#" Value="member this.GetQueuesAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;&gt;" Usage="namespaceManager.GetQueuesAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="b9b6b-450">Ruft asynchron eine aufzählbare Auflistung von alle Warteschlangen im Dienstnamespace ein.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-450">Asynchronously retrieves an enumerable collection of all queues in the service namespace.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-451">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-451">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetQueuesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;&gt; GetQueuesAsync (string filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.QueueDescription&gt;&gt; GetQueuesAsync(string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetQueuesAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetQueuesAsync (filter As String) As Task(Of IEnumerable(Of QueueDescription))" />
      <MemberSignature Language="F#" Value="member this.GetQueuesAsync : string -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;&gt;" Usage="namespaceManager.GetQueuesAsync filter" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="filter"><span data-ttu-id="b9b6b-452">Die Zeichenfolge, die zum Filtern der Warteschlangen abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-452">The string used to filter the queues to be retrieved.</span></span></param>
        <summary><span data-ttu-id="b9b6b-453">Asynchron Ruft eine aufzählbare Auflistung von alle Warteschlangen im Dienstnamespace mit angegebenen Filter ab.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-453">Asynchronously retrieves an enumerable collection of all queues in the service namespace with specified filter.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-454">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-454">The asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="b9b6b-455">Filtern von ausdrucksformaten: {aus} {logischer Operator} {Value} und {Filterausdruck} {Funktion} {logischer Operator} {Value} und {Filterausdruck}</span><span class="sxs-lookup"><span data-stu-id="b9b6b-455">Filter expression formats:  {Propery} {Logical Operator} {Value} AND {Filter expression} {Function} {Logical Operator} {Value} AND {Filter expression}</span></span>
                                        -----------------------------------------------------------------------------------------
            <span data-ttu-id="b9b6b-456">Verfügbare Eigenschaften: Pfad | ModifiedAt | AccessedAt | CreatedAt | MessageCount logische Operatoren: Eq | Ne | Gt | Ge | Lt | LE</span><span class="sxs-lookup"><span data-stu-id="b9b6b-456">Available properties:       Path | ModifiedAt | AccessedAt | CreatedAt | MessageCount Logical operators:          Eq | Ne | Gt | Ge | Lt | Le</span></span>  
            <span data-ttu-id="b9b6b-457">Wert: Geben Sie ein Wert der entsprechenden Eigenschaft Funktionen: "StartsWith" ({aus}, {Value})</span><span class="sxs-lookup"><span data-stu-id="b9b6b-457">Value:                      A value of the corresponding property type Functions:                  startswith({Propery}, {Value})</span></span>
            </remarks>
        <example>
          <code>
            <span data-ttu-id="b9b6b-458">Var QueuesWithMessages = "await" namespaceManager.GetQueuesAsync ("MessageCount Gt 0"); Var QueuesStartsWith = "await" namespaceManager.GetQueuesAsync ($"" StartsWith "(Pfad,"Queue") Eq" true "");</span><span class="sxs-lookup"><span data-stu-id="b9b6b-458">var queuesWithMessages = await namespaceManager.GetQueuesAsync("messageCount Gt 0"); var queuesStartsWith = await namespaceManager.GetQueuesAsync($"startswith(path, 'queue') eq true");</span></span>
            </code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="GetRelay">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.RelayDescription GetRelay (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.RelayDescription GetRelay(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetRelay(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRelay (path As String) As RelayDescription" />
      <MemberSignature Language="F#" Value="member this.GetRelay : string -&gt; Microsoft.ServiceBus.Messaging.RelayDescription" Usage="namespaceManager.GetRelay path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.RelayDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="b9b6b-459">Der relaypfad.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-459">The relay path.</span></span></param>
        <summary><span data-ttu-id="b9b6b-460">Ruft die Details eines bestimmten Relaydienst-Endpunkts ab.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-460">Retrieves the details of a given relay endpoint.</span></span></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRelayAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt; GetRelayAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.RelayDescription&gt; GetRelayAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetRelayAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRelayAsync (path As String) As Task(Of RelayDescription)" />
      <MemberSignature Language="F#" Value="member this.GetRelayAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt;" Usage="namespaceManager.GetRelayAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="b9b6b-461">Der relaypfad.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-461">The relay path.</span></span></param>
        <summary><span data-ttu-id="b9b6b-462">Ruft Sie die Details eines bestimmten Relaydienst-Endpunkts asynchron ab.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-462">Asynchronously retrieves the details of a given relay endpoint.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-463">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-463">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRelays">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt; GetRelays ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.RelayDescription&gt; GetRelays() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetRelays" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRelays () As IEnumerable(Of RelayDescription)" />
      <MemberSignature Language="F#" Value="member this.GetRelays : unit -&gt; seq&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt;" Usage="namespaceManager.GetRelays " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="b9b6b-464">Ruft eine Auflistung aller Relays im Dienstnamespace ab.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-464">Retrieves a collection of all relays in the service namespace.</span></span></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRelaysAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt;&gt; GetRelaysAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.RelayDescription&gt;&gt; GetRelaysAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetRelaysAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRelaysAsync () As Task(Of IEnumerable(Of RelayDescription))" />
      <MemberSignature Language="F#" Value="member this.GetRelaysAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt;&gt;" Usage="namespaceManager.GetRelaysAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceBus.NamespaceManager/&lt;GetRelaysAsync&gt;d__40))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="b9b6b-465">Eine Auflistung aller Relays im Dienstnamespace asynchron abgerufen.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-465">Asynchronously retrieves a collection of all relays in the service namespace.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-466">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-466">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRevokedPublishers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RevokedPublisherDescription&gt; GetRevokedPublishers (string entityPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.RevokedPublisherDescription&gt; GetRevokedPublishers(string entityPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetRevokedPublishers(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRevokedPublishers (entityPath As String) As IEnumerable(Of RevokedPublisherDescription)" />
      <MemberSignature Language="F#" Value="member this.GetRevokedPublishers : string -&gt; seq&lt;Microsoft.ServiceBus.Messaging.RevokedPublisherDescription&gt;" Usage="namespaceManager.GetRevokedPublishers entityPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RevokedPublisherDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityPath"><span data-ttu-id="b9b6b-467">Pfad zu den Event Hub.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-467">Path to the Event Hub.</span></span> <span data-ttu-id="b9b6b-468">Weitere Informationen finden Sie unter <see cref="P:Microsoft.ServiceBus.Messaging.EventHubDescription.Path" />.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-468">See <see cref="P:Microsoft.ServiceBus.Messaging.EventHubDescription.Path" />.</span></span></param>
        <summary><span data-ttu-id="b9b6b-469">Gibt alle widerrufenen Verleger in einem Event Hub zurück.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-469">Returns all revoked publishers in an Event Hub.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-470">Gibt eine <see cref="T:System.Collections.Generic.IEnumerable`1" /> Auflistung mit den gesperrten Verlegern.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-470">Returns an <see cref="T:System.Collections.Generic.IEnumerable`1" /> collection containing the revoked publishers.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRevokedPublishersAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RevokedPublisherDescription&gt;&gt; GetRevokedPublishersAsync (string entityPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.RevokedPublisherDescription&gt;&gt; GetRevokedPublishersAsync(string entityPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetRevokedPublishersAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRevokedPublishersAsync (entityPath As String) As Task(Of IEnumerable(Of RevokedPublisherDescription))" />
      <MemberSignature Language="F#" Value="member this.GetRevokedPublishersAsync : string -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.RevokedPublisherDescription&gt;&gt;" Usage="namespaceManager.GetRevokedPublishersAsync entityPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RevokedPublisherDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityPath"><span data-ttu-id="b9b6b-471">Pfad zu den Event Hub.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-471">Path to the Event Hub.</span></span> <span data-ttu-id="b9b6b-472">Weitere Informationen finden Sie unter <see cref="P:Microsoft.ServiceBus.Messaging.EventHubDescription.Path" />.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-472">See <see cref="P:Microsoft.ServiceBus.Messaging.EventHubDescription.Path" />.</span></span></param>
        <summary><span data-ttu-id="b9b6b-473">Asynchrone Version von <see cref="M:Microsoft.ServiceBus.NamespaceManager.GetRevokedPublishers(System.String)" />.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-473">Asynchronous version of <see cref="M:Microsoft.ServiceBus.NamespaceManager.GetRevokedPublishers(System.String)" />.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-474">Gibt eine <see cref="T:System.Threading.Tasks.Task`1" /> , die die gesperrten Verlegern enthält.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-474">Returns a <see cref="T:System.Threading.Tasks.Task`1" /> containing the revoked publishers.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RuleDescription&gt; GetRules (string topicPath, string subscriptionName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.RuleDescription&gt; GetRules(string topicPath, string subscriptionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetRules(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRules (topicPath As String, subscriptionName As String) As IEnumerable(Of RuleDescription)" />
      <MemberSignature Language="F#" Value="member this.GetRules : string * string -&gt; seq&lt;Microsoft.ServiceBus.Messaging.RuleDescription&gt;" Usage="namespaceManager.GetRules (topicPath, subscriptionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RuleDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath"><span data-ttu-id="b9b6b-475">Der Pfad des Themas relativ zur Basisadresse Diensts-Namespace.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-475">The path of the topic relative to the service namespace base address.</span></span></param>
        <param name="subscriptionName"><span data-ttu-id="b9b6b-476">Der Name des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-476">The name of the subscription.</span></span></param>
        <summary><span data-ttu-id="b9b6b-477">Ruft eine aufzählbare Auflistung aller Regeln im Dienstnamespace ab.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-477">Retrieves an enumerable collection of all rules in the service namespace.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-478">Ein <see cref="T:System.Collections.Generic.IEnumerable`1" /> -Objekt, das die Auflistung aller Regeln im Dienstnamespace oder eine leere Auflistung zurück, wenn keine Regel vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-478">An <see cref="T:System.Collections.Generic.IEnumerable`1" /> object that represents the collection of all rules in the service namespace or returns an empty collection if no rule exists.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RuleDescription&gt; GetRules (string topicPath, string subscriptionName, string filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.RuleDescription&gt; GetRules(string topicPath, string subscriptionName, string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetRules(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRules (topicPath As String, subscriptionName As String, filter As String) As IEnumerable(Of RuleDescription)" />
      <MemberSignature Language="F#" Value="member this.GetRules : string * string * string -&gt; seq&lt;Microsoft.ServiceBus.Messaging.RuleDescription&gt;" Usage="namespaceManager.GetRules (topicPath, subscriptionName, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RuleDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath"><span data-ttu-id="b9b6b-479">Der Themenname relativ zur Basisadresse Diensts-Namespace.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-479">The topic path relative to the service namespace base address.</span></span></param>
        <param name="subscriptionName"><span data-ttu-id="b9b6b-480">Der Name des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-480">The name of the subscription.</span></span></param>
        <param name="filter"><span data-ttu-id="b9b6b-481">Die Zeichenfolge, die zum Filtern der Regeln abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-481">The string used to filter the rules to be retrieved.</span></span></param>
        <summary><span data-ttu-id="b9b6b-482">Ruft eine aufzählbare Auflistung aller Regeln im Dienstnamespace mit angegebenen themenpfad, Abonnementnamen und Filter ab.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-482">Retrieves an enumerable collection of all rules in the service namespace with specified topic path, subscription name and filter.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-483">Ein <see cref="T:System.Collections.Generic.IEnumerable`1" /> -Objekt, das die Auflistung aller Regeln im Dienstnamespace oder eine leere Auflistung zurück, wenn keine Regel vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-483">An <see cref="T:System.Collections.Generic.IEnumerable`1" /> object that represents the collection of all rules in the service namespace or returns an empty collection if no rule exists.</span></span></returns>
        <remarks>
            <a name="filter-expression-format---propery-logical-operator-value-filter-expression"></a><span data-ttu-id="b9b6b-484">Filter-Ausdruck-Format: {aus} {logischer Operator} {Value} {Filterausdruck}</span><span class="sxs-lookup"><span data-stu-id="b9b6b-484">Filter expression format:   {Propery} {Logical Operator} {Value} {Filter expression}</span></span>
            -----------------------------------------------------------------------------------------
            <span data-ttu-id="b9b6b-485">Verfügbare Eigenschaften: ModifiedAt | AccessedAt | CreatedAt logische Operatoren: Eq | Ne | Gt | Ge | Lt | LE</span><span class="sxs-lookup"><span data-stu-id="b9b6b-485">Available properties:       ModifiedAt | AccessedAt | CreatedAt Logical operators:          Eq | Ne | Gt | Ge | Lt | Le</span></span>  
            <span data-ttu-id="b9b6b-486">Wert: Der Wert der entsprechenden Eigenschaftentyp</span><span class="sxs-lookup"><span data-stu-id="b9b6b-486">Value:                      A value of the corresponding property type</span></span>
            </remarks>
        <example>
          <code>
            <span data-ttu-id="b9b6b-487">Var FiveMinutesAgo = DateTime.UtcNow.AddMinutes(-5). ToString ("M/TT/JJJJ hh: mm:"); Var rulesInTheLast5Minutes = namespaceManager.GetRules (Name_des_themas, SubscriptionName "," $"CreatedAt Gt"{FiveMinutesAgo}"");</span><span class="sxs-lookup"><span data-stu-id="b9b6b-487">var fiveMinutesAgo = DateTime.UtcNow.AddMinutes(-5).ToString("M/dd/yyyy hh:mm:ss"); var rulesInTheLast5Minutes = namespaceManager.GetRules(topicName, subscriptionName, $"createdAt gt '{fiveMinutesAgo}'");</span></span>
            </code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="GetRulesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RuleDescription&gt;&gt; GetRulesAsync (string topicPath, string subscriptionName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.RuleDescription&gt;&gt; GetRulesAsync(string topicPath, string subscriptionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetRulesAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRulesAsync (topicPath As String, subscriptionName As String) As Task(Of IEnumerable(Of RuleDescription))" />
      <MemberSignature Language="F#" Value="member this.GetRulesAsync : string * string -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.RuleDescription&gt;&gt;" Usage="namespaceManager.GetRulesAsync (topicPath, subscriptionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RuleDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath"><span data-ttu-id="b9b6b-488">Der Themenname relativ zur Basisadresse Diensts-Namespace.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-488">The topic path relative to the service namespace base address.</span></span></param>
        <param name="subscriptionName"><span data-ttu-id="b9b6b-489">Der Name des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-489">The name of the subscription.</span></span></param>
        <summary><span data-ttu-id="b9b6b-490">Ruft asynchron eine aufzählbare Auflistung aller Regeln im Dienstnamespace ein.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-490">Asynchronously retrieves an enumerable collection of all rules in the service namespace.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-491">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-491">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRulesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RuleDescription&gt;&gt; GetRulesAsync (string topicPath, string subscriptionName, string filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.RuleDescription&gt;&gt; GetRulesAsync(string topicPath, string subscriptionName, string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetRulesAsync(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRulesAsync (topicPath As String, subscriptionName As String, filter As String) As Task(Of IEnumerable(Of RuleDescription))" />
      <MemberSignature Language="F#" Value="member this.GetRulesAsync : string * string * string -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.RuleDescription&gt;&gt;" Usage="namespaceManager.GetRulesAsync (topicPath, subscriptionName, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RuleDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath"><span data-ttu-id="b9b6b-492">Der Themenname relativ zur Basisadresse Diensts-Namespace.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-492">The topic path relative to the service namespace base address.</span></span></param>
        <param name="subscriptionName"><span data-ttu-id="b9b6b-493">Der Name des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-493">The name of the subscription.</span></span></param>
        <param name="filter"><span data-ttu-id="b9b6b-494">Die Zeichenfolge, die zum Filtern der Regeln abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-494">The string used to filter the rules to be retrieved.</span></span></param>
        <summary><span data-ttu-id="b9b6b-495">Ruft asynchron eine aufzählbare Auflistung aller Regeln im Dienstnamespace mit angegebenen themenpfad, Abonnementnamen und Filter ein.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-495">Asynchronously retrieves an enumerable collection of all rules in the service namespace with specified topic path, subscription name and filter.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-496">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-496">The asynchronous operation.</span></span></returns>
        <remarks>
            <a name="filter-expression-format---propery-logical-operator-value-filter-expression"></a><span data-ttu-id="b9b6b-497">Filter-Ausdruck-Format: {aus} {logischer Operator} {Value} {Filterausdruck}</span><span class="sxs-lookup"><span data-stu-id="b9b6b-497">Filter expression format:   {Propery} {Logical Operator} {Value} {Filter expression}</span></span>
            -----------------------------------------------------------------------------------------
            <span data-ttu-id="b9b6b-498">Verfügbare Eigenschaften: ModifiedAt | AccessedAt | CreatedAt logische Operatoren: Eq | Ne | Gt | Ge | Lt | LE</span><span class="sxs-lookup"><span data-stu-id="b9b6b-498">Available properties:       ModifiedAt | AccessedAt | CreatedAt Logical operators:          Eq | Ne | Gt | Ge | Lt | Le</span></span>  
            <span data-ttu-id="b9b6b-499">Wert: Der Wert der entsprechenden Eigenschaftentyp</span><span class="sxs-lookup"><span data-stu-id="b9b6b-499">Value:                      A value of the corresponding property type</span></span>
            </remarks>
        <example>
          <code>
            <span data-ttu-id="b9b6b-500">Var FiveMinutesAgo = DateTime.UtcNow.AddMinutes(-5). ToString ("M/TT/JJJJ hh: mm:"); Var rulesInTheLast5Minutes = "await" namespaceManager.GetRulesAsync (Name_des_themas, SubscriptionName "," $"CreatedAt Gt"{FiveMinutesAgo}"");</span><span class="sxs-lookup"><span data-stu-id="b9b6b-500">var fiveMinutesAgo = DateTime.UtcNow.AddMinutes(-5).ToString("M/dd/yyyy hh:mm:ss"); var rulesInTheLast5Minutes = await namespaceManager.GetRulesAsync(topicName, subscriptionName, $"createdAt gt '{fiveMinutesAgo}'");</span></span>
            </code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="GetSubscription">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.SubscriptionDescription GetSubscription (string topicPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.SubscriptionDescription GetSubscription(string topicPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetSubscription(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSubscription (topicPath As String, name As String) As SubscriptionDescription" />
      <MemberSignature Language="F#" Value="member this.GetSubscription : string * string -&gt; Microsoft.ServiceBus.Messaging.SubscriptionDescription" Usage="namespaceManager.GetSubscription (topicPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath"><span data-ttu-id="b9b6b-501">Der Pfad des Themas relativ zur Basisadresse Diensts-Namespace.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-501">The path of the topic relative to the service namespace base address.</span></span></param>
        <param name="name"><span data-ttu-id="b9b6b-502">Der Name des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-502">The name of the subscription.</span></span></param>
        <summary><span data-ttu-id="b9b6b-503">Ruft das Thema aus dem Dienstnamespace ab.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-503">Retrieves the topic from the service namespace.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-504">Ein <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> handle für das Abonnement oder eine <see cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException" /> -Ausnahme aus, wenn das Abonnement nicht im Dienstnamespace vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-504">A <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> handle to the subscription, or a <see cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException" /> exception if the subscription does not exist in the service namespace.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException"><span data-ttu-id="b9b6b-505">Das Abonnement ist nicht im Dienstnamespace vorhanden.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-505">The subscription does not exist in the service namespace.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetSubscriptionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; GetSubscriptionAsync (string topicPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; GetSubscriptionAsync(string topicPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetSubscriptionAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSubscriptionAsync (topicPath As String, name As String) As Task(Of SubscriptionDescription)" />
      <MemberSignature Language="F#" Value="member this.GetSubscriptionAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;" Usage="namespaceManager.GetSubscriptionAsync (topicPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath"><span data-ttu-id="b9b6b-506">Der Pfad des Themas relativ zur Basisadresse Diensts-Namespace.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-506">The path of the topic relative to the service namespace base address.</span></span></param>
        <param name="name"><span data-ttu-id="b9b6b-507">Der Name des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-507">The name of the subscription.</span></span></param>
        <summary><span data-ttu-id="b9b6b-508">Ruft asynchron Thema Dienstnamespace ab.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-508">Asynchronously retrieves the topic from the service namespace.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-509">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-509">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSubscriptions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; GetSubscriptions (string topicPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; GetSubscriptions(string topicPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetSubscriptions(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSubscriptions (topicPath As String) As IEnumerable(Of SubscriptionDescription)" />
      <MemberSignature Language="F#" Value="member this.GetSubscriptions : string -&gt; seq&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;" Usage="namespaceManager.GetSubscriptions topicPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath"><span data-ttu-id="b9b6b-510">Der Pfad des Themas relativ zur Basisadresse Diensts-Namespace.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-510">The path of the topic relative to the service namespace base address.</span></span></param>
        <summary><span data-ttu-id="b9b6b-511">Ruft eine aufzählbare Auflistung aller Abonnements im Dienstnamespace ab.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-511">Retrieves an enumerable collection of all subscriptions in the service namespace.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-512">Ein <see cref="T:System.Collections.Generic.IEnumerable`1" /> -Objekt, stellt die Auflistung aller Abonnements im Dienstnamespace oder eine leere Auflistung zurück, wenn kein Abonnement vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-512">An <see cref="T:System.Collections.Generic.IEnumerable`1" /> object that represents the collection of all subscriptions in the service namespace or returns an empty collection if no subscription exists.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSubscriptions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; GetSubscriptions (string topicPath, string filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; GetSubscriptions(string topicPath, string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetSubscriptions(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSubscriptions (topicPath As String, filter As String) As IEnumerable(Of SubscriptionDescription)" />
      <MemberSignature Language="F#" Value="member this.GetSubscriptions : string * string -&gt; seq&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;" Usage="namespaceManager.GetSubscriptions (topicPath, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath"><span data-ttu-id="b9b6b-513">Der Pfad des Themas relativ zur Basisadresse Diensts-Namespace.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-513">The path of the topic relative to the service namespace base address.</span></span></param>
        <param name="filter"><span data-ttu-id="b9b6b-514">Die Zeichenfolge, die zum Filtern von Abonnements abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-514">The string used to filter the subscriptions to be retrieved.</span></span></param>
        <summary><span data-ttu-id="b9b6b-515">Ruft eine aufzählbare Auflistung aller Abonnements im Dienstnamespace angegebenen themenpfad und Filter ab.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-515">Retrieves an enumerable collection of all subscriptions in the service namespace with specified topic path and filter.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-516">Ein <see cref="T:System.Collections.Generic.IEnumerable`1" /> -Objekt, stellt die Auflistung aller Abonnements im Dienstnamespace oder eine leere Auflistung zurück, wenn kein Abonnement vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-516">An <see cref="T:System.Collections.Generic.IEnumerable`1" /> object that represents the collection of all subscriptions in the service namespace or returns an empty collection if no subscription exists.</span></span></returns>
        <remarks>
            <span data-ttu-id="b9b6b-517">Filtern von ausdrucksformaten: {aus} {logischer Operator} {Value} und {Filterausdruck} {Funktion} {logischer Operator} {Value} und {Filterausdruck}</span><span class="sxs-lookup"><span data-stu-id="b9b6b-517">Filter expression formats:  {Propery} {Logical Operator} {Value} AND {Filter expression} {Function} {Logical Operator} {Value} AND {Filter expression}</span></span>
                                        -----------------------------------------------------------------------------------------
            <span data-ttu-id="b9b6b-518">Verfügbare Eigenschaften: ModifiedAt | AccessedAt | CreatedAt | MessageCount logische Operatoren: Eq | Ne | Gt | Ge | Lt | LE</span><span class="sxs-lookup"><span data-stu-id="b9b6b-518">Available properties:       ModifiedAt | AccessedAt | CreatedAt | MessageCount Logical operators:          Eq | Ne | Gt | Ge | Lt | Le</span></span>  
            <span data-ttu-id="b9b6b-519">Wert: Geben Sie ein Wert der entsprechenden Eigenschaft Funktionen: "StartsWith" ({aus}, {Value})</span><span class="sxs-lookup"><span data-stu-id="b9b6b-519">Value:                      A value of the corresponding property type Functions:                  startswith({Propery}, {Value})</span></span>
            </remarks>
        <example>
          <code>
            <span data-ttu-id="b9b6b-520">Var SubscriptionsWithMessages = namespaceManager.GetSubscriptions ("Name_des_themas", "MessageCount Gt 0"); Var SubscriptionsStartsWith = namespaceManager.GetSubscriptions ("Name_des_themas", $"" StartsWith "(Pfad, 'Abonnement') Eq"true "");</span><span class="sxs-lookup"><span data-stu-id="b9b6b-520">var subscriptionsWithMessages = namespaceManager.GetSubscriptions("topicName", "messageCount Gt 0"); var subscriptionsStartsWith = namespaceManager.GetSubscriptions("topicName", $"startswith(path, 'subscription') eq true");</span></span>
            </code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="GetSubscriptionsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;&gt; GetSubscriptionsAsync (string topicPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;&gt; GetSubscriptionsAsync(string topicPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetSubscriptionsAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSubscriptionsAsync (topicPath As String) As Task(Of IEnumerable(Of SubscriptionDescription))" />
      <MemberSignature Language="F#" Value="member this.GetSubscriptionsAsync : string -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;&gt;" Usage="namespaceManager.GetSubscriptionsAsync topicPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath"><span data-ttu-id="b9b6b-521">Der Pfad des Themas relativ zur Basisadresse Diensts-Namespace.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-521">The path of the topic relative to the service namespace base address.</span></span></param>
        <summary><span data-ttu-id="b9b6b-522">Ruft asynchron eine aufzählbare Auflistung aller Abonnements im Dienstnamespace ein.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-522">Asynchronously retrieves an enumerable collection of all subscriptions in the service namespace.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-523">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-523">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSubscriptionsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;&gt; GetSubscriptionsAsync (string topicPath, string filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;&gt; GetSubscriptionsAsync(string topicPath, string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetSubscriptionsAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSubscriptionsAsync (topicPath As String, filter As String) As Task(Of IEnumerable(Of SubscriptionDescription))" />
      <MemberSignature Language="F#" Value="member this.GetSubscriptionsAsync : string * string -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;&gt;" Usage="namespaceManager.GetSubscriptionsAsync (topicPath, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath"><span data-ttu-id="b9b6b-524">Der Pfad des Themas relativ zur Basisadresse Diensts-Namespace.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-524">The path of the topic relative to the service namespace base address.</span></span></param>
        <param name="filter"><span data-ttu-id="b9b6b-525">Die Zeichenfolge, die zum Filtern von Abonnements abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-525">The string used to filter the subscriptions to be retrieved.</span></span></param>
        <summary><span data-ttu-id="b9b6b-526">Ruft asynchron eine aufzählbare Auflistung aller Abonnements im Dienstnamespace ein.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-526">Asynchronously retrieves an enumerable collection of all subscriptions in the service namespace.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-527">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-527">The asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="b9b6b-528">Filtern von ausdrucksformaten: {aus} {logischer Operator} {Value} und {Filterausdruck} {Funktion} {logischer Operator} {Value} und {Filterausdruck}</span><span class="sxs-lookup"><span data-stu-id="b9b6b-528">Filter expression formats:  {Propery} {Logical Operator} {Value} AND {Filter expression} {Function} {Logical Operator} {Value} AND {Filter expression}</span></span>
                                        -----------------------------------------------------------------------------------------
            <span data-ttu-id="b9b6b-529">Verfügbare Eigenschaften: ModifiedAt | AccessedAt | CreatedAt | MessageCount logische Operatoren: Eq | Ne | Gt | Ge | Lt | LE</span><span class="sxs-lookup"><span data-stu-id="b9b6b-529">Available properties:       ModifiedAt | AccessedAt | CreatedAt | MessageCount Logical operators:          Eq | Ne | Gt | Ge | Lt | Le</span></span>  
            <span data-ttu-id="b9b6b-530">Wert: Geben Sie ein Wert der entsprechenden Eigenschaft Funktionen: "StartsWith" ({aus}, {Value})</span><span class="sxs-lookup"><span data-stu-id="b9b6b-530">Value:                      A value of the corresponding property type Functions:                  startswith({Propery}, {Value})</span></span>
            </remarks>
        <example>
          <code>
            <span data-ttu-id="b9b6b-531">Var SubscriptionsWithMessages = "await" namespaceManager.GetSubscriptionsAsync ("Name_des_themas", "MessageCount Gt 0"); Var SubscriptionsStartsWith = "await" namespaceManager.GetSubscriptionsAsync ("Name_des_themas", $"" StartsWith "(Pfad, 'Abonnement') Eq"true "");</span><span class="sxs-lookup"><span data-stu-id="b9b6b-531">var subscriptionsWithMessages = await namespaceManager.GetSubscriptionsAsync("topicName", "messageCount Gt 0"); var subscriptionsStartsWith = await namespaceManager.GetSubscriptionsAsync("topicName", $"startswith(path, 'subscription') eq true");</span></span>
            </code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="GetTopic">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.TopicDescription GetTopic (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.TopicDescription GetTopic(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetTopic(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetTopic (path As String) As TopicDescription" />
      <MemberSignature Language="F#" Value="member this.GetTopic : string -&gt; Microsoft.ServiceBus.Messaging.TopicDescription" Usage="namespaceManager.GetTopic path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TopicDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="b9b6b-532">Der Pfad des Themas relativ zur Basisadresse Diensts-Namespace.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-532">The path of the topic relative to the service namespace base address.</span></span></param>
        <summary><span data-ttu-id="b9b6b-533">Ruft das Thema aus dem Dienstnamespace ab.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-533">Retrieves the topic from the service namespace.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-534">Ein <see cref="T:Microsoft.ServiceBus.Messaging.TopicDescription" /> Verweis auf das Thema oder ein <see cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException" /> -Ausnahme aus, wenn das Thema nicht im Dienstnamespace vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-534">A <see cref="T:Microsoft.ServiceBus.Messaging.TopicDescription" /> reference to the topic, or a <see cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException" /> exception if the topic does not exist in the service namespace.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="b9b6b-535"><paramref name="path" />ist leer oder null.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-535"><paramref name="path" /> is empty or null.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="b9b6b-536">Timeout des Vorgangs. Das Zeitlimit wird initialisiert, durch die <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> Klasse.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-536">The operation times out. The timeout period is initialized through the <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> class.</span></span> <span data-ttu-id="b9b6b-537">Sie müssen möglicherweise den Wert erhöhen die <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" /> Eigenschaft, um diese Ausnahme zu vermeiden, wenn der Timeoutwert relativ gering ist.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-537">You may need to increase the value of the <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" /> property to avoid this exception if the timeout value is relatively low.</span></span></exception>
        <exception cref="T:System.UnauthorizedAccessException"><span data-ttu-id="b9b6b-538">Die <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> Objekt verfügt nicht über ausreichende Berechtigungen zum Ausführen dieses Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-538">The <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> object does not have sufficient permission to perform this operation.</span></span> <span data-ttu-id="b9b6b-539">Sie sollten prüfen, um sicherzustellen, dass Ihre <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> verfügt über den richtigen <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.TokenProvider" /> Anmeldeinformationen zum Ausführen dieses Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-539">You should check to ensure that your <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> has the correct <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.TokenProvider" /> credentials to perform this operation.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException"><span data-ttu-id="b9b6b-540">Das Thema im Dienstnamespace ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-540">The topic does not exist in the service namespace.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException"><span data-ttu-id="b9b6b-541">Ein interner Fehler oder unerwartete Ausnahme auftritt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-541">An internal error or unexpected exception occurs.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetTopicAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt; GetTopicAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.TopicDescription&gt; GetTopicAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetTopicAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetTopicAsync (path As String) As Task(Of TopicDescription)" />
      <MemberSignature Language="F#" Value="member this.GetTopicAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;" Usage="namespaceManager.GetTopicAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="b9b6b-542">Der Pfad des Themas relativ zur Basisadresse Diensts-Namespace.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-542">The path of the topic relative to the service namespace base address.</span></span></param>
        <summary><span data-ttu-id="b9b6b-543">Ruft asynchron Thema Dienstnamespace ab.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-543">Asynchronously retrieves the topic from the service namespace.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-544">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-544">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTopics">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt; GetTopics ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.TopicDescription&gt; GetTopics() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetTopics" />
      <MemberSignature Language="VB.NET" Value="Public Function GetTopics () As IEnumerable(Of TopicDescription)" />
      <MemberSignature Language="F#" Value="member this.GetTopics : unit -&gt; seq&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;" Usage="namespaceManager.GetTopics " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="b9b6b-545">Ruft eine Auflistung der Themen in einem Dienstnamespace ab.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-545">Retrieves a collection of topics in a service namespace.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-546">Ein <see cref="T:System.Collections.Generic.IEnumerable`1" /> -Objekt, stellt die Auflistung der Themen, unter dem aktuellen Namespace oder eine leere Auflistung zurück, wenn kein Thema vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-546">An <see cref="T:System.Collections.Generic.IEnumerable`1" /> object that represents the collection of topics under the current namespace, or returns an empty collection if no topic exists.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="b9b6b-547">Timeout des Vorgangs. Das Zeitlimit wird initialisiert, durch die <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> Klasse.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-547">The operation times out. The timeout period is initialized through the <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> class.</span></span> <span data-ttu-id="b9b6b-548">Sie müssen möglicherweise den Wert erhöhen die <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" /> Eigenschaft, um diese Ausnahme zu vermeiden, wenn der Timeoutwert relativ gering ist.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-548">You may need to increase the value of the <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" /> property to avoid this exception if the timeout value is relatively low.</span></span></exception>
        <exception cref="T:System.UnauthorizedAccessException"><span data-ttu-id="b9b6b-549">Die <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> Objekt verfügt nicht über ausreichende Berechtigungen zum Ausführen dieses Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-549">The <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> object does not have sufficient permission to perform this operation.</span></span> <span data-ttu-id="b9b6b-550">Sie sollten prüfen, um sicherzustellen, dass Ihre <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> verfügt über den richtigen <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.TokenProvider" /> Anmeldeinformationen zum Ausführen dieses Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-550">You should check to ensure that your <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> has the correct <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.TokenProvider" /> credentials to perform this operation.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException"><span data-ttu-id="b9b6b-551">Ein interner Fehler oder unerwartete Ausnahme auftritt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-551">An internal error or unexpected exception occurs.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetTopics">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt; GetTopics (string filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.TopicDescription&gt; GetTopics(string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetTopics(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetTopics (filter As String) As IEnumerable(Of TopicDescription)" />
      <MemberSignature Language="F#" Value="member this.GetTopics : string -&gt; seq&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;" Usage="namespaceManager.GetTopics filter" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="filter"><span data-ttu-id="b9b6b-552">Die Zeichenfolge, die zum Filtern der Themen abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-552">The string used to filter the topics to be retrieved.</span></span></param>
        <summary><span data-ttu-id="b9b6b-553">Ruft eine Auflistung von Themen in einem Dienstnamespace mit dem angegebenen Filter ab.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-553">Retrieves a collection of topics in a service namespace with the specified filter.</span></span> <span data-ttu-id="b9b6b-554">Sie können durch eine Kombination von Entitätsname (einschließlich beginnt mit), Entität Länge (Gt oder Lt), erstellt, aktualisiert und Zugriffs-Zeit (Gt oder Lt) filtern.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-554">You can filter by a combination of entity name (including starts with), entity length (Gt or Lt), created, updated, and accessed time (Gt or Lt).</span></span></summary>
        <returns><span data-ttu-id="b9b6b-555">Ein <see cref="T:System.Collections.Generic.IEnumerable`1" /> -Objekt, stellt die Auflistung der Themen, unter dem aktuellen Namespace oder eine leere Auflistung zurück, wenn kein Thema vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-555">An <see cref="T:System.Collections.Generic.IEnumerable`1" /> object that represents the collection of topics under the current namespace, or returns an empty collection if no topic exists.</span></span></returns>
        <remarks>
            <span data-ttu-id="b9b6b-556">Filtern von ausdrucksformaten: {aus} {logischer Operator} {Value} und {Filterausdruck} {Funktion} {logischer Operator} {Value} und {Filterausdruck}</span><span class="sxs-lookup"><span data-stu-id="b9b6b-556">Filter expression formats:  {Propery} {Logical Operator} {Value} AND {Filter expression} {Function} {Logical Operator} {Value} AND {Filter expression}</span></span>
                                        -----------------------------------------------------------------------------------------
            <span data-ttu-id="b9b6b-557">Verfügbare Eigenschaften: Pfad | ModifiedAt | AccessedAt | CreatedAt | MessageCount logische Operatoren: Eq | Ne | Gt | Ge | Lt | LE</span><span class="sxs-lookup"><span data-stu-id="b9b6b-557">Available properties:       Path | ModifiedAt | AccessedAt | CreatedAt | MessageCount Logical operators:          Eq | Ne | Gt | Ge | Lt | Le</span></span>  
            <span data-ttu-id="b9b6b-558">Wert: Geben Sie ein Wert der entsprechenden Eigenschaft Funktionen: "StartsWith" ({aus}, {Value})</span><span class="sxs-lookup"><span data-stu-id="b9b6b-558">Value:                      A value of the corresponding property type Functions:                  startswith({Propery}, {Value})</span></span>
            </remarks>
        <example>
          <code>
            <span data-ttu-id="b9b6b-559">Var TopicsWithMessages = namespaceManager.GetTopics ("MessageCount Gt 0"); Var TopicsStartsWith = namespaceManager.GetTopics ($"" StartsWith "(Pfad,"Thema") Eq" true "");</span><span class="sxs-lookup"><span data-stu-id="b9b6b-559">var topicsWithMessages = namespaceManager.GetTopics("messageCount Gt 0"); var topicsStartsWith = namespaceManager.GetTopics($"startswith(path, 'topic') eq true");</span></span>
            </code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="GetTopicsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;&gt; GetTopicsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.TopicDescription&gt;&gt; GetTopicsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetTopicsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetTopicsAsync () As Task(Of IEnumerable(Of TopicDescription))" />
      <MemberSignature Language="F#" Value="member this.GetTopicsAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;&gt;" Usage="namespaceManager.GetTopicsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="b9b6b-560">Eine Auflistung der Themen in einem Dienstnamespace asynchron abgerufen.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-560">Asynchronously retrieves a collection of topics in a service namespace.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-561">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-561">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTopicsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;&gt; GetTopicsAsync (string filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.TopicDescription&gt;&gt; GetTopicsAsync(string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetTopicsAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetTopicsAsync (filter As String) As Task(Of IEnumerable(Of TopicDescription))" />
      <MemberSignature Language="F#" Value="member this.GetTopicsAsync : string -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;&gt;" Usage="namespaceManager.GetTopicsAsync filter" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="filter"><span data-ttu-id="b9b6b-562">Die Zeichenfolge, die zum Filtern der Themen abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-562">The string used to filter the topics to be retrieved.</span></span></param>
        <summary><span data-ttu-id="b9b6b-563">Eine Auflistung der Themen in einem Dienstnamespace asynchron abgerufen.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-563">Asynchronously retrieves a collection of topics in a service namespace.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-564">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-564">The asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="b9b6b-565">Filtern von ausdrucksformaten: {aus} {logischer Operator} {Value} und {Filterausdruck} {Funktion} {logischer Operator} {Value} und {Filterausdruck}</span><span class="sxs-lookup"><span data-stu-id="b9b6b-565">Filter expression formats:  {Propery} {Logical Operator} {Value} AND {Filter expression} {Function} {Logical Operator} {Value} AND {Filter expression}</span></span>
                                        -----------------------------------------------------------------------------------------
            <span data-ttu-id="b9b6b-566">Verfügbare Eigenschaften: Pfad | ModifiedAt | AccessedAt | CreatedAt | MessageCount logische Operatoren: Eq | Ne | Gt | Ge | Lt | LE</span><span class="sxs-lookup"><span data-stu-id="b9b6b-566">Available properties:       Path | ModifiedAt | AccessedAt | CreatedAt | MessageCount Logical operators:          Eq | Ne | Gt | Ge | Lt | Le</span></span>  
            <span data-ttu-id="b9b6b-567">Wert: Geben Sie ein Wert der entsprechenden Eigenschaft Funktionen: "StartsWith" ({aus}, {Value})</span><span class="sxs-lookup"><span data-stu-id="b9b6b-567">Value:                      A value of the corresponding property type Functions:                  startswith({Propery}, {Value})</span></span>
            </remarks>
        <example>
          <code>
            <span data-ttu-id="b9b6b-568">Var TopicsWithMessages = "await" namespaceManager.GetTopicsAsync ("MessageCount Gt 0"); Var TopicsStartsWith = "await" namespaceManager.GetTopicsAsync ($"" StartsWith "(Pfad,"Thema") Eq" true "");</span><span class="sxs-lookup"><span data-stu-id="b9b6b-568">var topicsWithMessages = await namespaceManager.GetTopicsAsync("messageCount Gt 0"); var topicsStartsWith = await namespaceManager.GetTopicsAsync($"startswith(path, 'topic') eq true");</span></span>
            </code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="GetVersionInfo">
      <MemberSignature Language="C#" Value="public string GetVersionInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetVersionInfo() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetVersionInfo" />
      <MemberSignature Language="VB.NET" Value="Public Function GetVersionInfo () As String" />
      <MemberSignature Language="F#" Value="member this.GetVersionInfo : unit -&gt; string" Usage="namespaceManager.GetVersionInfo " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="b9b6b-569">Ruft eine Zeichenfolge im Format "YYYY-MM", die die maximal unterstützte Protokollversion angibt, die den Server oder-Dienst verarbeiten kann.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-569">Retrieves a string of the format "YYYY-MM" that indicates the maximum supported protocol version that the server or service can handle.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-570">Eine Zeichenfolge, die maximal unterstützte Protokollversion angibt, die den Server oder-Dienst verarbeiten kann.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-570">A string that indicates the maximum supported protocol version that the server or service can handle.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVersionInfoAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetVersionInfoAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; GetVersionInfoAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetVersionInfoAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetVersionInfoAsync () As Task(Of String)" />
      <MemberSignature Language="F#" Value="member this.GetVersionInfoAsync : unit -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="namespaceManager.GetVersionInfoAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="b9b6b-571">Asynchron Ruft eine Zeichenfolge im Format "YYYY-MM", die die maximal unterstützte Protokollversion angibt, die den Server oder-Dienst verarbeiten kann.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-571">Asynchronously retrieves a string of the format "YYYY-MM" that indicates the maximum supported protocol version that the server or service can handle.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-572">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-572">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtocolVersion">
      <MemberSignature Language="C#" Value="public const string ProtocolVersion;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string ProtocolVersion" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.NamespaceManager.ProtocolVersion" />
      <MemberSignature Language="VB.NET" Value="Public Const ProtocolVersion As String " />
      <MemberSignature Language="F#" Value="val mutable ProtocolVersion : string" Usage="Microsoft.ServiceBus.NamespaceManager.ProtocolVersion" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="b9b6b-573">Gibt die Zeichenfolge im Format "YYYY-MM", die die Client-Protokollversion angibt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-573">Specifies the string of the format "YYYY-MM" that indicates the client protocol version.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QueueExists">
      <MemberSignature Language="C#" Value="public bool QueueExists (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool QueueExists(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.QueueExists(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function QueueExists (path As String) As Boolean" />
      <MemberSignature Language="F#" Value="member this.QueueExists : string -&gt; bool" Usage="namespaceManager.QueueExists path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="b9b6b-574">Der Pfad der Warteschlange relativ zur Basisadresse Diensts-Namespace.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-574">The path of the queue relative to the service namespace base address.</span></span></param>
        <summary><span data-ttu-id="b9b6b-575">Bestimmt, ob eine Warteschlange im Dienstnamespace vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-575">Determines whether a queue exists in the service namespace.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-576">"true", wenn eine Warteschlange im Dienstnamespace vorhanden ist; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="b9b6b-576">true if a queue exists in the service namespace; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QueueExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; QueueExistsAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;bool&gt; QueueExistsAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.QueueExistsAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function QueueExistsAsync (path As String) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.QueueExistsAsync : string -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="namespaceManager.QueueExistsAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="b9b6b-577">Der Pfad der Warteschlange relativ zur Basisadresse Diensts-Namespace.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-577">The path of the queue relative to the service namespace base address.</span></span></param>
        <summary><span data-ttu-id="b9b6b-578">Ermittelt asynchron, ob eine Warteschlange im Dienstnamespace vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-578">Asynchronously determines whether a queue exists in the service namespace.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-579">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-579">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RelayExists">
      <MemberSignature Language="C#" Value="public bool RelayExists (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool RelayExists(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.RelayExists(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RelayExists (path As String) As Boolean" />
      <MemberSignature Language="F#" Value="member this.RelayExists : string -&gt; bool" Usage="namespaceManager.RelayExists path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="b9b6b-580">Der Pfad des Relays relativ zur Basisadresse Diensts-Namespace.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-580">The path of the relay relative to the service namespace base address.</span></span></param>
        <summary><span data-ttu-id="b9b6b-581">Bestimmt, ob ein Relay im Dienstnamespace vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-581">Determines whether a relay exists in the service namespace.</span></span></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RelayExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; RelayExistsAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;bool&gt; RelayExistsAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.RelayExistsAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RelayExistsAsync (path As String) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RelayExistsAsync : string -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="namespaceManager.RelayExistsAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceBus.NamespaceManager/&lt;RelayExistsAsync&gt;d__42))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="b9b6b-582">Der Pfad des Relays relativ zur Basisadresse Diensts-Namespace.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-582">The path of the relay relative to the service namespace base address.</span></span></param>
        <summary><span data-ttu-id="b9b6b-583">Ermittelt asynchron, ob ein Relay im Dienstnamespace vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-583">Asynchronously determines whether a relay exists in the service namespace.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-584">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-584">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RenameQueue">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.QueueDescription RenameQueue (string path, string newPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.QueueDescription RenameQueue(string path, string newPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.RenameQueue(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RenameQueue (path As String, newPath As String) As QueueDescription" />
      <MemberSignature Language="F#" Value="member this.RenameQueue : string * string -&gt; Microsoft.ServiceBus.Messaging.QueueDescription" Usage="namespaceManager.RenameQueue (path, newPath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="newPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="b9b6b-585">Der Pfad zu einer vorhandenen Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-585">The path to an existing queue.</span></span></param>
        <param name="newPath"><span data-ttu-id="b9b6b-586">Der neue Pfad an die Warteschlange umbenannt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-586">The new path to the renamed queue.</span></span></param>
        <summary><span data-ttu-id="b9b6b-587">Benennt eine Warteschlange in einem Namespace an.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-587">Renames a queue inside a namespace.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-588">Gibt <see cref="T:Microsoft.ServiceBus.Messaging.QueueDescription" />zurück.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-588">Returns <see cref="T:Microsoft.ServiceBus.Messaging.QueueDescription" />.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="b9b6b-589">Wird ausgelöst, wenn <paramref name="path" /> ist null oder leer.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-589">Thrown when <paramref name="path" /> is null or empty.</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="b9b6b-590">Wird ausgelöst, wenn die Länge des <paramref name="path" /> beträgt mehr als 290 Zeichen.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-590">Thrown when the length of <paramref name="path" /> is more than 290 characters.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="b9b6b-591">Wird ausgelöst, wenn der Vorgang ein Timeout auftritt. Das Zeitlimit wird initialisiert, durch die <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> Klasse.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-591">Thrown when the operation times out. The timeout period is initialized through the <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> class.</span></span> <span data-ttu-id="b9b6b-592">Sie können den Wert der erhöhen die <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" /> Eigenschaft, um diese Ausnahme zu vermeiden, wenn der Timeoutwert relativ gering ist.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-592">You can increase the value of the <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" /> property to avoid this exception if the timeout value is relatively low.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException"><span data-ttu-id="b9b6b-593">Wird ausgelöst, wenn die Quellwarteschlange mit dem angegebenen Pfad nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-593">Thrown when the source queue with the specified path does not exist.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityAlreadyExistsException"><span data-ttu-id="b9b6b-594">Wird ausgelöst, wenn die Zielwarteschlange mit dem gleichen Pfad innerhalb des gleichen Namespace vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-594">Thrown when the target queue with the same path exists within the same namespace.</span></span></exception>
        <exception cref="T:System.UnauthorizedAccessException"><span data-ttu-id="b9b6b-595">Wird ausgelöst, wenn der Client die Anmeldeinformationen zum Ausführen des Vorgangs nicht besitzt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-595">Thrown when the client does not have credentials to perform the operation.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException"><span data-ttu-id="b9b6b-596">Wird ausgelöst, wenn ein interner Fehler oder unerwartete Ausnahme auftritt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-596">Thrown when an internal error or unexpected exception occurs.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RenameQueueAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt; RenameQueueAsync (string path, string newPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.QueueDescription&gt; RenameQueueAsync(string path, string newPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.RenameQueueAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RenameQueueAsync (path As String, newPath As String) As Task(Of QueueDescription)" />
      <MemberSignature Language="F#" Value="member this.RenameQueueAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;" Usage="namespaceManager.RenameQueueAsync (path, newPath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="newPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="b9b6b-597">Der Pfad zu einer vorhandenen Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-597">The path to an existing queue.</span></span></param>
        <param name="newPath"><span data-ttu-id="b9b6b-598">Der neue Pfad an die Warteschlange umbenannt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-598">The new path to the renamed queue.</span></span></param>
        <summary><span data-ttu-id="b9b6b-599">Asynchrone Version von <see cref="M:Microsoft.ServiceBus.NamespaceManager.RenameQueue(System.String,System.String)" />.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-599">Asynchronous version of <see cref="M:Microsoft.ServiceBus.NamespaceManager.RenameQueue(System.String,System.String)" />.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-600">Gibt <see cref="T:System.Threading.Tasks.Task`1" />zurück.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-600">Returns <see cref="T:System.Threading.Tasks.Task`1" />.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="b9b6b-601">Wird ausgelöst, wenn <paramref name="path" /> ist null oder leer.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-601">Thrown when <paramref name="path" /> is null or empty.</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="b9b6b-602">Wird ausgelöst, wenn die Länge des <paramref name="path" /> beträgt mehr als 290 Zeichen.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-602">Thrown when the length of <paramref name="path" /> is more than 290 characters.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="b9b6b-603">Wird ausgelöst, wenn der Vorgang ein Timeout auftritt. Das Zeitlimit wird initialisiert, durch die <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> Klasse.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-603">Thrown when the operation times out. The timeout period is initialized through the <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> class.</span></span> <span data-ttu-id="b9b6b-604">Sie können den Wert der erhöhen die <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" /> Eigenschaft, um diese Ausnahme zu vermeiden, wenn der Timeoutwert relativ gering ist.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-604">You can increase the value of the <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" /> property to avoid this exception if the timeout value is relatively low.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException"><span data-ttu-id="b9b6b-605">Wird ausgelöst, wenn die Quellwarteschlange mit dem angegebenen Pfad nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-605">Thrown when the source queue with the specified path does not exist.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityAlreadyExistsException"><span data-ttu-id="b9b6b-606">Wird ausgelöst, wenn die Zielwarteschlange mit dem gleichen Pfad innerhalb des gleichen Namespace vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-606">Thrown when the target queue with the same path exists within the same namespace.</span></span></exception>
        <exception cref="T:System.UnauthorizedAccessException"><span data-ttu-id="b9b6b-607">Wird ausgelöst, wenn der Client die Anmeldeinformationen zum Ausführen des Vorgangs nicht besitzt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-607">Thrown when the client does not have credentials to perform the operation.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException"><span data-ttu-id="b9b6b-608">Wird ausgelöst, wenn ein interner Fehler oder unerwartete Ausnahme auftritt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-608">Thrown when an internal error or unexpected exception occurs.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RenameTopic">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.TopicDescription RenameTopic (string path, string newPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.TopicDescription RenameTopic(string path, string newPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.RenameTopic(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RenameTopic (path As String, newPath As String) As TopicDescription" />
      <MemberSignature Language="F#" Value="member this.RenameTopic : string * string -&gt; Microsoft.ServiceBus.Messaging.TopicDescription" Usage="namespaceManager.RenameTopic (path, newPath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TopicDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="newPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="b9b6b-609">Der Pfad auf ein vorhandenes Thema.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-609">The path to an existing topic.</span></span></param>
        <param name="newPath"><span data-ttu-id="b9b6b-610">Der neue Pfad an das umbenannte Thema.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-610">The new path to the renamed topic.</span></span></param>
        <summary><span data-ttu-id="b9b6b-611">Benennt ein Thema in einem Namespace an.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-611">Renames a topic inside a namespace.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-612">Gibt <see cref="T:Microsoft.ServiceBus.Messaging.TopicDescription" />zurück.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-612">Returns <see cref="T:Microsoft.ServiceBus.Messaging.TopicDescription" />.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="b9b6b-613">Wird ausgelöst, wenn <paramref name="path" /> ist null oder leer.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-613">Thrown when <paramref name="path" /> is null or empty.</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="b9b6b-614">Wird ausgelöst, wenn die Länge des <paramref name="path" /> beträgt mehr als 290 Zeichen.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-614">Thrown when the length of <paramref name="path" /> is more than 290 characters.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="b9b6b-615">Wird ausgelöst, wenn der Vorgang ein Timeout auftritt. Das Zeitlimit wird initialisiert, durch die <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> Klasse.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-615">Thrown when the operation times out. The timeout period is initialized through the <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> class.</span></span> <span data-ttu-id="b9b6b-616">Sie können den Wert der erhöhen die <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" /> Eigenschaft, um diese Ausnahme zu vermeiden, wenn der Timeoutwert relativ gering ist.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-616">You can increase the value of the <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" /> property to avoid this exception if the timeout value is relatively low.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException"><span data-ttu-id="b9b6b-617">Wird ausgelöst, wenn das quellthema mit dem angegebenen Pfad nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-617">Thrown when the source topic with the specified path does not exist.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityAlreadyExistsException"><span data-ttu-id="b9b6b-618">Wird ausgelöst, wenn das Zielthema mit dem gleichen Pfad innerhalb des gleichen Namespace vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-618">Thrown when the target topic with the same path exists within the same namespace.</span></span></exception>
        <exception cref="T:System.UnauthorizedAccessException"><span data-ttu-id="b9b6b-619">Wird ausgelöst, wenn der Client die Anmeldeinformationen zum Ausführen des Vorgangs nicht besitzt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-619">Thrown when the client does not have credentials to perform the operation.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException"><span data-ttu-id="b9b6b-620">Wird ausgelöst, wenn ein interner Fehler oder unerwartete Ausnahme auftritt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-620">Thrown when an internal error or unexpected exception occurs.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RenameTopicAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt; RenameTopicAsync (string path, string newPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.TopicDescription&gt; RenameTopicAsync(string path, string newPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.RenameTopicAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RenameTopicAsync (path As String, newPath As String) As Task(Of TopicDescription)" />
      <MemberSignature Language="F#" Value="member this.RenameTopicAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;" Usage="namespaceManager.RenameTopicAsync (path, newPath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="newPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="b9b6b-621">Der Pfad auf ein vorhandenes Thema.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-621">The path to an existing topic.</span></span></param>
        <param name="newPath"><span data-ttu-id="b9b6b-622">Der neue Pfad an das umbenannte Thema.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-622">The new path to the renamed topic.</span></span></param>
        <summary><span data-ttu-id="b9b6b-623">Asynchrone Version von <see cref="M:Microsoft.ServiceBus.NamespaceManager.RenameTopic(System.String,System.String)" />.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-623">Asynchronous version of <see cref="M:Microsoft.ServiceBus.NamespaceManager.RenameTopic(System.String,System.String)" />.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-624">Gibt <see cref="T:System.Threading.Tasks.Task`1" />zurück.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-624">Returns <see cref="T:System.Threading.Tasks.Task`1" />.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="b9b6b-625">Wird ausgelöst, wenn <paramref name="path" /> ist null oder leer.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-625">Thrown when <paramref name="path" /> is null or empty.</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="b9b6b-626">Wird ausgelöst, wenn die Länge des <paramref name="path" /> beträgt mehr als 290 Zeichen.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-626">Thrown when the length of <paramref name="path" /> is more than 290 characters.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="b9b6b-627">Wird ausgelöst, wenn der Vorgang ein Timeout auftritt. Das Zeitlimit wird initialisiert, durch die <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> Klasse.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-627">Thrown when the operation times out. The timeout period is initialized through the <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> class.</span></span> <span data-ttu-id="b9b6b-628">Sie können den Wert der erhöhen die <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" /> Eigenschaft, um diese Ausnahme zu vermeiden, wenn der Timeoutwert relativ gering ist.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-628">You can increase the value of the <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" /> property to avoid this exception if the timeout value is relatively low.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException"><span data-ttu-id="b9b6b-629">Wird ausgelöst, wenn das quellthema mit dem angegebenen Pfad nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-629">Thrown when the source topic with the specified path does not exist.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityAlreadyExistsException"><span data-ttu-id="b9b6b-630">Wird ausgelöst, wenn das Zielthema mit dem gleichen Pfad innerhalb des gleichen Namespace vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-630">Thrown when the target topic with the same path exists within the same namespace.</span></span></exception>
        <exception cref="T:System.UnauthorizedAccessException"><span data-ttu-id="b9b6b-631">Wird ausgelöst, wenn der Client die Anmeldeinformationen zum Ausführen des Vorgangs nicht besitzt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-631">Thrown when the client does not have credentials to perform the operation.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException"><span data-ttu-id="b9b6b-632">Wird ausgelöst, wenn ein interner Fehler oder unerwartete Ausnahme auftritt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-632">Thrown when an internal error or unexpected exception occurs.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestorePublisher">
      <MemberSignature Language="C#" Value="public void RestorePublisher (string entityPath, string publisher);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RestorePublisher(string entityPath, string publisher) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.RestorePublisher(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RestorePublisher (entityPath As String, publisher As String)" />
      <MemberSignature Language="F#" Value="member this.RestorePublisher : string * string -&gt; unit" Usage="namespaceManager.RestorePublisher (entityPath, publisher)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="publisher" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityPath"><span data-ttu-id="b9b6b-633">Ereignis-Hub Pfad unter dem der Verleger wurde gesperrt und muss wiederhergestellt werden.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-633">Event Hub path under which the publisher was revoked and must be restored.</span></span> <span data-ttu-id="b9b6b-634">Weitere Informationen finden Sie unter <see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" />.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-634">See <see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" />.</span></span></param>
        <param name="publisher"><span data-ttu-id="b9b6b-635">Der gesperrten Herausgeber.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-635">The revoked publisher.</span></span></param>
        <summary><span data-ttu-id="b9b6b-636">Entfernt den Verleger aus der Sperrliste Event Hubs.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-636">Removes the publisher from the Event Hubs revocation list.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestorePublisherAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RestorePublisherAsync (string entityPath, string publisher);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RestorePublisherAsync(string entityPath, string publisher) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.RestorePublisherAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RestorePublisherAsync (entityPath As String, publisher As String) As Task" />
      <MemberSignature Language="F#" Value="member this.RestorePublisherAsync : string * string -&gt; System.Threading.Tasks.Task" Usage="namespaceManager.RestorePublisherAsync (entityPath, publisher)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="publisher" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityPath"><span data-ttu-id="b9b6b-637">Ereignis-Hub Pfad unter dem der Verleger wurde gesperrt und muss wiederhergestellt werden.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-637">Event Hub path under which the publisher was revoked and must be restored.</span></span> <span data-ttu-id="b9b6b-638">Weitere Informationen finden Sie unter <see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" />.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-638">See <see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" />.</span></span></param>
        <param name="publisher"><span data-ttu-id="b9b6b-639">Der gesperrten Herausgeber.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-639">The revoked publisher.</span></span></param>
        <summary><span data-ttu-id="b9b6b-640">Asynchrone Version von <see cref="M:Microsoft.ServiceBus.NamespaceManager.RestorePublisher(System.String,System.String)" />.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-640">Asynchronous version of <see cref="M:Microsoft.ServiceBus.NamespaceManager.RestorePublisher(System.String,System.String)" />.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-641">Gibt <see cref="T:System.Threading.Tasks.Task" />zurück.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-641">Returns <see cref="T:System.Threading.Tasks.Task" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RevokePublisher">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.RevokedPublisherDescription RevokePublisher (string entityPath, string publisher);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.RevokedPublisherDescription RevokePublisher(string entityPath, string publisher) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.RevokePublisher(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RevokePublisher (entityPath As String, publisher As String) As RevokedPublisherDescription" />
      <MemberSignature Language="F#" Value="member this.RevokePublisher : string * string -&gt; Microsoft.ServiceBus.Messaging.RevokedPublisherDescription" Usage="namespaceManager.RevokePublisher (entityPath, publisher)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.RevokedPublisherDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="publisher" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityPath"><span data-ttu-id="b9b6b-642">Event Hub-Pfad, unter dem der Verleger aufgehoben werden muss.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-642">Event Hub path under which the publisher must be revoked.</span></span> <span data-ttu-id="b9b6b-643">Weitere Informationen finden Sie unter <see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" />.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-643">See <see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" />.</span></span></param>
        <param name="publisher"><span data-ttu-id="b9b6b-644">Der Herausgeber aufzuheben.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-644">The publisher to revoke.</span></span></param>
        <summary><span data-ttu-id="b9b6b-645">Fügt den Verleger wurde der Sperrliste Event Hubs.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-645">Adds the publisher to the Event Hubs revocation list.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-646">Gibt <see cref="T:Microsoft.ServiceBus.Messaging.RevokedPublisherDescription" />zurück.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-646">Returns <see cref="T:Microsoft.ServiceBus.Messaging.RevokedPublisherDescription" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RevokePublisherAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.RevokedPublisherDescription&gt; RevokePublisherAsync (string entityPath, string publisher);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.RevokedPublisherDescription&gt; RevokePublisherAsync(string entityPath, string publisher) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.RevokePublisherAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RevokePublisherAsync (entityPath As String, publisher As String) As Task(Of RevokedPublisherDescription)" />
      <MemberSignature Language="F#" Value="member this.RevokePublisherAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.RevokedPublisherDescription&gt;" Usage="namespaceManager.RevokePublisherAsync (entityPath, publisher)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.RevokedPublisherDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="publisher" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityPath"><span data-ttu-id="b9b6b-647">Event Hub-Pfad, unter dem der Verleger aufgehoben werden muss.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-647">Event Hub path under which the publisher must be revoked.</span></span> <span data-ttu-id="b9b6b-648">Weitere Informationen finden Sie unter <see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" />.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-648">See <see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" />.</span></span></param>
        <param name="publisher"><span data-ttu-id="b9b6b-649">Der Herausgeber aufzuheben.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-649">The publisher to revoke.</span></span></param>
        <summary><span data-ttu-id="b9b6b-650">Asynchrone Version von <see cref="M:Microsoft.ServiceBus.NamespaceManager.RevokePublisher(System.String,System.String)" />.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-650">Asynchronous version of <see cref="M:Microsoft.ServiceBus.NamespaceManager.RevokePublisher(System.String,System.String)" />.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-651">Gibt <see cref="T:System.Threading.Tasks.Task`1" />zurück.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-651">Returns <see cref="T:System.Threading.Tasks.Task`1" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Settings">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.NamespaceManagerSettings Settings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.NamespaceManagerSettings Settings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NamespaceManager.Settings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Settings As NamespaceManagerSettings" />
      <MemberSignature Language="F#" Value="member this.Settings : Microsoft.ServiceBus.NamespaceManagerSettings" Usage="Microsoft.ServiceBus.NamespaceManager.Settings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.NamespaceManagerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="b9b6b-652">Ruft den Namespace-Dienstclient Einstellungen ab.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-652">Gets the service namespace client settings.</span></span></summary>
        <value><span data-ttu-id="b9b6b-653">Ein <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> Objekt, das die Clienteinstellungen des Dienst-Namespace darstellt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-653">A <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> object that represents the service namespace client settings.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionExists">
      <MemberSignature Language="C#" Value="public bool SubscriptionExists (string topicPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool SubscriptionExists(string topicPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.SubscriptionExists(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SubscriptionExists (topicPath As String, name As String) As Boolean" />
      <MemberSignature Language="F#" Value="member this.SubscriptionExists : string * string -&gt; bool" Usage="namespaceManager.SubscriptionExists (topicPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath"><span data-ttu-id="b9b6b-654">Der Pfad des Themas relativ zur Basisadresse Diensts-Namespace.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-654">The path of the topic relative to the service namespace base address.</span></span></param>
        <param name="name"><span data-ttu-id="b9b6b-655">Der Name des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-655">The name of the subscription.</span></span></param>
        <summary><span data-ttu-id="b9b6b-656">Bestimmt, ob ein Abonnement im Dienstnamespace vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-656">Determines whether a subscription exists in the service namespace.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-657">True, wenn ein Abonnement vorhanden ist, im Dienstnamespace. andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="b9b6b-657">true if a subscription exists in the service namespace; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; SubscriptionExistsAsync (string topicPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;bool&gt; SubscriptionExistsAsync(string topicPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.SubscriptionExistsAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SubscriptionExistsAsync (topicPath As String, name As String) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.SubscriptionExistsAsync : string * string -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="namespaceManager.SubscriptionExistsAsync (topicPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath"><span data-ttu-id="b9b6b-658">Der Pfad des Themas relativ zur Basisadresse Diensts-Namespace.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-658">The path of the topic relative to the service namespace base address.</span></span></param>
        <param name="name"><span data-ttu-id="b9b6b-659">Der Name des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-659">The name of the subscription.</span></span></param>
        <summary><span data-ttu-id="b9b6b-660">Ermittelt asynchron, ob ein Abonnement im Dienstnamespace vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-660">Asynchronously determines whether a subscription exists in the service namespace.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-661">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-661">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TopicExists">
      <MemberSignature Language="C#" Value="public bool TopicExists (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool TopicExists(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.TopicExists(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function TopicExists (path As String) As Boolean" />
      <MemberSignature Language="F#" Value="member this.TopicExists : string -&gt; bool" Usage="namespaceManager.TopicExists path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="b9b6b-662">Der Pfad des Themas relativ zur Basisadresse Diensts-Namespace.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-662">The path of the topic relative to the service namespace base address.</span></span></param>
        <summary><span data-ttu-id="b9b6b-663">Bestimmt, ob im Dienstnamespace ein Thema vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-663">Determines whether a topic exists in the service namespace.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-664">"true", wenn ein Thema vorhanden, im Dienstnamespace ist; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="b9b6b-664">true if a topic exists in the service namespace; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TopicExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; TopicExistsAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;bool&gt; TopicExistsAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.TopicExistsAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function TopicExistsAsync (path As String) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.TopicExistsAsync : string -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="namespaceManager.TopicExistsAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="b9b6b-665">Der Pfad des Themas relativ zur Basisadresse Diensts-Namespace.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-665">The path of the topic relative to the service namespace base address.</span></span></param>
        <summary><span data-ttu-id="b9b6b-666">Ermittelt asynchron, ob im Dienstnamespace ein Thema vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-666">Asynchronously determines whether a topic exists in the service namespace.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-667">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-667">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateConsumerGroup">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.ConsumerGroupDescription UpdateConsumerGroup (Microsoft.ServiceBus.Messaging.ConsumerGroupDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription UpdateConsumerGroup(class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.UpdateConsumerGroup(Microsoft.ServiceBus.Messaging.ConsumerGroupDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateConsumerGroup (description As ConsumerGroupDescription) As ConsumerGroupDescription" />
      <MemberSignature Language="F#" Value="member this.UpdateConsumerGroup : Microsoft.ServiceBus.Messaging.ConsumerGroupDescription -&gt; Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" Usage="namespaceManager.UpdateConsumerGroup description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.ConsumerGroupDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="b9b6b-668">Ein <see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" /> Objekt, das die aktualisierte Informationen enthält.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-668">A <see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" /> object containing the updated information.</span></span></param>
        <summary><span data-ttu-id="b9b6b-669">Aktualisiert eine Event Hubs-Consumer-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-669">Updates an Event Hubs consumer group.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-670">Gibt <see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />zurück.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-670">Returns <see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateConsumerGroupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt; UpdateConsumerGroupAsync (Microsoft.ServiceBus.Messaging.ConsumerGroupDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt; UpdateConsumerGroupAsync(class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.UpdateConsumerGroupAsync(Microsoft.ServiceBus.Messaging.ConsumerGroupDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateConsumerGroupAsync (description As ConsumerGroupDescription) As Task(Of ConsumerGroupDescription)" />
      <MemberSignature Language="F#" Value="member this.UpdateConsumerGroupAsync : Microsoft.ServiceBus.Messaging.ConsumerGroupDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;" Usage="namespaceManager.UpdateConsumerGroupAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="b9b6b-671">Die Beschreibung für den Consumer-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-671">The consumer group description.</span></span></param>
        <summary><span data-ttu-id="b9b6b-672">Aktualisiert asynchron die consumergruppe.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-672">Asynchronously updates the consumer group.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-673">Die Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-673">The task representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateEventHub">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventHubDescription UpdateEventHub (Microsoft.ServiceBus.Messaging.EventHubDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventHubDescription UpdateEventHub(class Microsoft.ServiceBus.Messaging.EventHubDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.UpdateEventHub(Microsoft.ServiceBus.Messaging.EventHubDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateEventHub (description As EventHubDescription) As EventHubDescription" />
      <MemberSignature Language="F#" Value="member this.UpdateEventHub : Microsoft.ServiceBus.Messaging.EventHubDescription -&gt; Microsoft.ServiceBus.Messaging.EventHubDescription" Usage="namespaceManager.UpdateEventHub description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.EventHubDescription" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="b9b6b-674">Ein <see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" /> Objekt, das die aktualisierte Informationen enthält.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-674">An <see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" /> object containing the updated information.</span></span></param>
        <summary><span data-ttu-id="b9b6b-675">Aktualisiert den Event Hub.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-675">Updates an Event Hub.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-676">Gibt <see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" />zurück.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-676">Returns <see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateEventHubAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt; UpdateEventHubAsync (Microsoft.ServiceBus.Messaging.EventHubDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.EventHubDescription&gt; UpdateEventHubAsync(class Microsoft.ServiceBus.Messaging.EventHubDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.UpdateEventHubAsync(Microsoft.ServiceBus.Messaging.EventHubDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateEventHubAsync (description As EventHubDescription) As Task(Of EventHubDescription)" />
      <MemberSignature Language="F#" Value="member this.UpdateEventHubAsync : Microsoft.ServiceBus.Messaging.EventHubDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt;" Usage="namespaceManager.UpdateEventHubAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.EventHubDescription" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="b9b6b-677">Der Hub-Beschreibung des Ereignisses.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-677">The event hub description.</span></span></param>
        <summary><span data-ttu-id="b9b6b-678">Asynchron aktualisiert den Event Hub.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-678">Asynchronously updates the event hub.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-679">Die Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-679">The task representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateQueue">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.QueueDescription UpdateQueue (Microsoft.ServiceBus.Messaging.QueueDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.QueueDescription UpdateQueue(class Microsoft.ServiceBus.Messaging.QueueDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.UpdateQueue(Microsoft.ServiceBus.Messaging.QueueDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateQueue (description As QueueDescription) As QueueDescription" />
      <MemberSignature Language="F#" Value="member this.UpdateQueue : Microsoft.ServiceBus.Messaging.QueueDescription -&gt; Microsoft.ServiceBus.Messaging.QueueDescription" Usage="namespaceManager.UpdateQueue description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.QueueDescription" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="b9b6b-680">Ein <see cref="T:Microsoft.ServiceBus.Messaging.QueueDescription" /> -Objekt, beschreibt der Warteschlange aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-680">A <see cref="T:Microsoft.ServiceBus.Messaging.QueueDescription" /> object describing the queue to be updated.</span></span></param>
        <summary><span data-ttu-id="b9b6b-681">Können Sie die Warteschlange zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-681">Enables you to update the queue.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-682">Die <see cref="T:Microsoft.ServiceBus.Messaging.QueueDescription" /> von der Warteschlange aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-682">The <see cref="T:Microsoft.ServiceBus.Messaging.QueueDescription" /> of the updated queue.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateQueueAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt; UpdateQueueAsync (Microsoft.ServiceBus.Messaging.QueueDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.QueueDescription&gt; UpdateQueueAsync(class Microsoft.ServiceBus.Messaging.QueueDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.UpdateQueueAsync(Microsoft.ServiceBus.Messaging.QueueDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateQueueAsync (description As QueueDescription) As Task(Of QueueDescription)" />
      <MemberSignature Language="F#" Value="member this.UpdateQueueAsync : Microsoft.ServiceBus.Messaging.QueueDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;" Usage="namespaceManager.UpdateQueueAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.QueueDescription" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="b9b6b-683">Ein <see cref="T:Microsoft.ServiceBus.Messaging.QueueDescription" /> -Objekt, beschreibt der Warteschlange aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-683">A <see cref="T:Microsoft.ServiceBus.Messaging.QueueDescription" /> object describing the queue to be updated.</span></span></param>
        <summary><span data-ttu-id="b9b6b-684">Asynchron können Sie die Warteschlange zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-684">Asynchronously enables you to update the queue.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-685">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-685">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateRelay">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.RelayDescription UpdateRelay (Microsoft.ServiceBus.Messaging.RelayDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.RelayDescription UpdateRelay(class Microsoft.ServiceBus.Messaging.RelayDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.UpdateRelay(Microsoft.ServiceBus.Messaging.RelayDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateRelay (description As RelayDescription) As RelayDescription" />
      <MemberSignature Language="F#" Value="member this.UpdateRelay : Microsoft.ServiceBus.Messaging.RelayDescription -&gt; Microsoft.ServiceBus.Messaging.RelayDescription" Usage="namespaceManager.UpdateRelay description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.RelayDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.RelayDescription" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="b9b6b-686">Ein <see cref="T:Microsoft.ServiceBus.Messaging.RelayDescription" /> -Objekt, das aktualisierte Relay beschreibt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-686">A <see cref="T:Microsoft.ServiceBus.Messaging.RelayDescription" /> object describing the updated relay.</span></span></param>
        <summary><span data-ttu-id="b9b6b-687">Upddates einen relayendpunkt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-687">Upddates a relay endpoint.</span></span></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateRelayAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt; UpdateRelayAsync (Microsoft.ServiceBus.Messaging.RelayDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.RelayDescription&gt; UpdateRelayAsync(class Microsoft.ServiceBus.Messaging.RelayDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.UpdateRelayAsync(Microsoft.ServiceBus.Messaging.RelayDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateRelayAsync (description As RelayDescription) As Task(Of RelayDescription)" />
      <MemberSignature Language="F#" Value="member this.UpdateRelayAsync : Microsoft.ServiceBus.Messaging.RelayDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt;" Usage="namespaceManager.UpdateRelayAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.RelayDescription" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="b9b6b-688">Ein <see cref="T:Microsoft.ServiceBus.Messaging.RelayDescription" /> -Objekt, das aktualisierte Relay beschreibt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-688">A <see cref="T:Microsoft.ServiceBus.Messaging.RelayDescription" /> object describing the updated relay.</span></span></param>
        <summary><span data-ttu-id="b9b6b-689">Asynchron Upddates einen relayendpunkt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-689">Asynchronously upddates a relay endpoint.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-690">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-690">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateSubscription">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.SubscriptionDescription UpdateSubscription (Microsoft.ServiceBus.Messaging.SubscriptionDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.SubscriptionDescription UpdateSubscription(class Microsoft.ServiceBus.Messaging.SubscriptionDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.UpdateSubscription(Microsoft.ServiceBus.Messaging.SubscriptionDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateSubscription (description As SubscriptionDescription) As SubscriptionDescription" />
      <MemberSignature Language="F#" Value="member this.UpdateSubscription : Microsoft.ServiceBus.Messaging.SubscriptionDescription -&gt; Microsoft.ServiceBus.Messaging.SubscriptionDescription" Usage="namespaceManager.UpdateSubscription description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.SubscriptionDescription" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="b9b6b-691">Ein <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> -Objekt, das Abonnement zu aktualisierenden beschreibt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-691">A <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> object describing the subscription to be updated.</span></span></param>
        <summary><span data-ttu-id="b9b6b-692">Ermöglicht es Ihnen, beim Aktualisieren des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-692">Enables you to update the subscription.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-693">Die <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> des aktualisierten Abonnements.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-693">The <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> of the updated subscription.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateSubscriptionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; UpdateSubscriptionAsync (Microsoft.ServiceBus.Messaging.SubscriptionDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; UpdateSubscriptionAsync(class Microsoft.ServiceBus.Messaging.SubscriptionDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.UpdateSubscriptionAsync(Microsoft.ServiceBus.Messaging.SubscriptionDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateSubscriptionAsync (description As SubscriptionDescription) As Task(Of SubscriptionDescription)" />
      <MemberSignature Language="F#" Value="member this.UpdateSubscriptionAsync : Microsoft.ServiceBus.Messaging.SubscriptionDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;" Usage="namespaceManager.UpdateSubscriptionAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.SubscriptionDescription" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="b9b6b-694">Ein <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> -Objekt, das Abonnement zu aktualisierenden beschreibt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-694">A <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> object describing the subscription to be updated.</span></span></param>
        <summary><span data-ttu-id="b9b6b-695">Asynchron können Sie das Abonnement aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-695">Asynchronously enables you to update the subscription.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-696">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-696">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTopic">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.TopicDescription UpdateTopic (Microsoft.ServiceBus.Messaging.TopicDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.TopicDescription UpdateTopic(class Microsoft.ServiceBus.Messaging.TopicDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.UpdateTopic(Microsoft.ServiceBus.Messaging.TopicDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateTopic (description As TopicDescription) As TopicDescription" />
      <MemberSignature Language="F#" Value="member this.UpdateTopic : Microsoft.ServiceBus.Messaging.TopicDescription -&gt; Microsoft.ServiceBus.Messaging.TopicDescription" Usage="namespaceManager.UpdateTopic description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TopicDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.TopicDescription" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="b9b6b-697">Ein <see cref="T:Microsoft.ServiceBus.Messaging.TopicDescription" /> -Objekt, das im Thema zu aktualisierenden beschreibt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-697">A <see cref="T:Microsoft.ServiceBus.Messaging.TopicDescription" /> object describing the topic to be updated.</span></span></param>
        <summary><span data-ttu-id="b9b6b-698">Ermöglicht Ihnen das Thema zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-698">Enables you to update the topic.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-699">Die <see cref="T:Microsoft.ServiceBus.Messaging.TopicDescription" /> des aktuellen Themas.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-699">The <see cref="T:Microsoft.ServiceBus.Messaging.TopicDescription" /> of the updated topic.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTopicAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt; UpdateTopicAsync (Microsoft.ServiceBus.Messaging.TopicDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.TopicDescription&gt; UpdateTopicAsync(class Microsoft.ServiceBus.Messaging.TopicDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.UpdateTopicAsync(Microsoft.ServiceBus.Messaging.TopicDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateTopicAsync (description As TopicDescription) As Task(Of TopicDescription)" />
      <MemberSignature Language="F#" Value="member this.UpdateTopicAsync : Microsoft.ServiceBus.Messaging.TopicDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;" Usage="namespaceManager.UpdateTopicAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.TopicDescription" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="b9b6b-700">Ein <see cref="T:Microsoft.ServiceBus.Messaging.TopicDescription" /> -Objekt, das im Thema zu aktualisierenden beschreibt.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-700">A <see cref="T:Microsoft.ServiceBus.Messaging.TopicDescription" /> object describing the topic to be updated.</span></span></param>
        <summary><span data-ttu-id="b9b6b-701">Asynchron können Sie das Thema zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-701">Asynchronously enables you to update the topic.</span></span></summary>
        <returns><span data-ttu-id="b9b6b-702">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="b9b6b-702">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>