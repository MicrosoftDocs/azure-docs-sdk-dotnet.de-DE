<Type Name="NamespaceManager" FullName="Microsoft.Azure.NotificationHubs.NamespaceManager">
  <TypeSignature Language="C#" Value="public sealed class NamespaceManager" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NamespaceManager extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.NamespaceManager" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NamespaceManager" />
  <TypeSignature Language="F#" Value="type NamespaceManager = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="230dd-101">Stellt eine Premium-Klasse, die bei der Verwaltung von Entitäten, z. B. Warteschlangen, Themen, Abonnements und Regeln in Ihren Dienstnamespace dar.</span><span class="sxs-lookup"><span data-stu-id="230dd-101">Represents an anchor class used in managing entities, such as queues, topics, subscriptions, and rules, in your service namespace.</span></span> <span data-ttu-id="230dd-102">Sie müssen Dienstnamespace Adresse und den Zugriff Anmeldeinformationen angeben, um Ihren Dienstnamespace zu verwalten.</span><span class="sxs-lookup"><span data-stu-id="230dd-102">You must provide service namespace address and access credentials in order to manage your service namespace.</span></span></summary>
    <remarks>To be added.</remarks>
    <example>
      <code>
             <span data-ttu-id="230dd-103">NamespaceManagerSettings NsSettings = neue NamespaceManagerSettings(); mit den Anmeldeinformationen und Vorgang Timeout NamespaceManager-Manager neue NamespaceManager = (neue Uri("baseUri"), NsSettings);</span><span class="sxs-lookup"><span data-stu-id="230dd-103">NamespaceManagerSettings nsSettings =  new NamespaceManagerSettings(); // with credentials and operation timeout NamespaceManager manager = new NamespaceManager(new Uri("baseUri"), NsSettings);</span></span>
              </code>
    </example>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (System.Collections.Generic.IEnumerable&lt;string&gt; addresses);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;string&gt; addresses) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.#ctor(System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (addresses As IEnumerable(Of String))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.NamespaceManager : seq&lt;string&gt; -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="new Microsoft.Azure.NotificationHubs.NamespaceManager addresses" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="addresses"><span data-ttu-id="230dd-104">Die vollständige Adressen des dienstnamespaces.</span><span class="sxs-lookup"><span data-stu-id="230dd-104">The full addresses of the service namespace.</span></span></param>
        <summary><span data-ttu-id="230dd-105">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> Klasse mit den angegebenen Adressen.</span><span class="sxs-lookup"><span data-stu-id="230dd-105">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> class with the given addresses.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="230dd-106">Wird ausgelöst, wenn Adressen Feld null ist.</span><span class="sxs-lookup"><span data-stu-id="230dd-106">Thrown when addresses field is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="230dd-107">Ausgelöst, wenn die Liste der Adressen null oder leer ist.</span><span class="sxs-lookup"><span data-stu-id="230dd-107">Thrown when addresses list is null or empty.</span></span></exception>
        <exception cref="T:System.UriFormatException"><span data-ttu-id="230dd-108">Ausgelöst, wenn die Adresse nicht richtig formatiert ist.</span><span class="sxs-lookup"><span data-stu-id="230dd-108">Thrown when address is not correctly formed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (System.Collections.Generic.IEnumerable&lt;Uri&gt; addresses);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; addresses) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.#ctor(System.Collections.Generic.IEnumerable{System.Uri})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (addresses As IEnumerable(Of Uri))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.NamespaceManager : seq&lt;Uri&gt; -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="new Microsoft.Azure.NotificationHubs.NamespaceManager addresses" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
      </Parameters>
      <Docs>
        <param name="addresses"><span data-ttu-id="230dd-109">Der vollständige URI-Adressen des dienstnamespaces.</span><span class="sxs-lookup"><span data-stu-id="230dd-109">The full URI addresses of the service namespace.</span></span></param>
        <summary><span data-ttu-id="230dd-110">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> Klasse mit den angegebenen Dienst Namespace-URI-Basisadressen.</span><span class="sxs-lookup"><span data-stu-id="230dd-110">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> class with the given service namespace URI base addresses.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="230dd-111">Wird ausgelöst, wenn Adressen Feld null ist.</span><span class="sxs-lookup"><span data-stu-id="230dd-111">Thrown when addresses field is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="230dd-112">Ausgelöst, wenn die Liste der Adressen null oder leer ist.</span><span class="sxs-lookup"><span data-stu-id="230dd-112">Thrown when addresses list is null or empty.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (string address);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (address As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.NamespaceManager : string -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="new Microsoft.Azure.NotificationHubs.NamespaceManager address" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="230dd-113">Die vollständige Adresse des dienstnamespaces.</span><span class="sxs-lookup"><span data-stu-id="230dd-113">The full address of the service namespace.</span></span></param>
        <summary><span data-ttu-id="230dd-114">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> Klasse mit dem angegebenen Namespace Dienstadresse.</span><span class="sxs-lookup"><span data-stu-id="230dd-114">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> class with the given service namespace address.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="230dd-115">Wird ausgelöst, wenn Adresse null ist.</span><span class="sxs-lookup"><span data-stu-id="230dd-115">Thrown when address is null.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (Uri address);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.#ctor(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (address As Uri)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.NamespaceManager : Uri -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="new Microsoft.Azure.NotificationHubs.NamespaceManager address" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="230dd-116">Die vollständige URI-Adresse des dienstnamespaces.</span><span class="sxs-lookup"><span data-stu-id="230dd-116">The full URI address of the service namespace.</span></span></param>
        <summary><span data-ttu-id="230dd-117">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> Klasse mit der angegebenen Service Namespace-URI-Basisadresse.</span><span class="sxs-lookup"><span data-stu-id="230dd-117">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> class with the given service namespace URI base address.</span></span> </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="230dd-118">Wird ausgelöst, wenn Adresse null ist.</span><span class="sxs-lookup"><span data-stu-id="230dd-118">Thrown when address is null.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (System.Collections.Generic.IEnumerable&lt;string&gt; addresses, Microsoft.Azure.NotificationHubs.NamespaceManagerSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;string&gt; addresses, class Microsoft.Azure.NotificationHubs.NamespaceManagerSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.#ctor(System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.NotificationHubs.NamespaceManagerSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (addresses As IEnumerable(Of String), settings As NamespaceManagerSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.NamespaceManager : seq&lt;string&gt; * Microsoft.Azure.NotificationHubs.NamespaceManagerSettings -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="new Microsoft.Azure.NotificationHubs.NamespaceManager (addresses, settings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="settings" Type="Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" />
      </Parameters>
      <Docs>
        <param name="addresses"><span data-ttu-id="230dd-119">Die vollständige Adressen des dienstnamespaces.</span><span class="sxs-lookup"><span data-stu-id="230dd-119">The full addresses of the service namespace.</span></span></param>
        <param name="settings"><span data-ttu-id="230dd-120">Ein <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" /> -Objekt, das enthält die <see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.Credential" /> und <see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.OperationTimeout" /> Eigenschaften.</span><span class="sxs-lookup"><span data-stu-id="230dd-120">A <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" /> object, which contains the <see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.Credential" /> and <see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.OperationTimeout" /> properties.</span></span></param>
        <summary><span data-ttu-id="230dd-121">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> Klasse mit dem angegebenen Adressen und Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="230dd-121">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> class with the given addresses and settings.</span></span></summary>
        <remarks>
            <span data-ttu-id="230dd-122">Obwohl es nicht zulässig ist, Pfade in der Namespace-Adresse enthalten, können Sie die Anmeldeinformationen, die nur auf einige Unterebenen von Basisadressen Aktionen autorisiert angeben, d. h. es ist kein, die die Anmeldeinformationen, die Sie angeben, auf der Basis Adressen Itse sein muss LF</span><span class="sxs-lookup"><span data-stu-id="230dd-122">Even though it is not allowed to include paths in the namespace address, you can specify a credential that authorizes you to perform actions only on some sublevels off of the base addresses, i.e. it is not a must that the credentials you specify be to the base adresses itself</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="230dd-123">Wird ausgelöst, wenn Adresse oder Einstellungen ist null.</span><span class="sxs-lookup"><span data-stu-id="230dd-123">Thrown when address or settings is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="230dd-124">Ausgelöst, wenn die Liste der Adressen null oder leer ist.</span><span class="sxs-lookup"><span data-stu-id="230dd-124">Thrown when addresses list is null or empty.</span></span></exception>
        <exception cref="T:System.UriFormatException"><span data-ttu-id="230dd-125">Ausgelöst, wenn die Adresse nicht richtig formatiert ist.</span><span class="sxs-lookup"><span data-stu-id="230dd-125">Thrown when address is not correctly formed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (System.Collections.Generic.IEnumerable&lt;string&gt; addresses, Microsoft.Azure.NotificationHubs.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;string&gt; addresses, class Microsoft.Azure.NotificationHubs.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.#ctor(System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.NotificationHubs.TokenProvider)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.NamespaceManager : seq&lt;string&gt; * Microsoft.Azure.NotificationHubs.TokenProvider -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="new Microsoft.Azure.NotificationHubs.NamespaceManager (addresses, tokenProvider)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="tokenProvider" Type="Microsoft.Azure.NotificationHubs.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="addresses"><span data-ttu-id="230dd-126">Die vollständige Adressen des dienstnamespaces.</span><span class="sxs-lookup"><span data-stu-id="230dd-126">The full addresses of the service namespace.</span></span></param>
        <param name="tokenProvider"><span data-ttu-id="230dd-127">Der Sicherheitstokenanbieter.</span><span class="sxs-lookup"><span data-stu-id="230dd-127">The security token provider.</span></span></param>
        <summary><span data-ttu-id="230dd-128">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> Klasse mit dem angegebenen Adressen und Anbieter von Sicherheitstoken.</span><span class="sxs-lookup"><span data-stu-id="230dd-128">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> class with the given addresses and token provider.</span></span></summary>
        <remarks>
            <span data-ttu-id="230dd-129">Obwohl es nicht zulässig ist die Namespace-Adressen Pfade einschließt, können Sie Anmeldeinformationen angeben, die nur auf einige Unterebenen von Basisadressen Aktionen autorisiert.</span><span class="sxs-lookup"><span data-stu-id="230dd-129">Even though it is not allowed to include paths in the namespace addresses, you can specify a credential that authorizes you to perform actions only on some sublevels off of the base addresses.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="230dd-130">Wird ausgelöst, wenn Adressen Feld null ist.</span><span class="sxs-lookup"><span data-stu-id="230dd-130">Thrown when addresses field is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="230dd-131">Ausgelöst, wenn die Liste der Adressen null oder leer ist.</span><span class="sxs-lookup"><span data-stu-id="230dd-131">Thrown when addresses list is null or empty.</span></span></exception>
        <exception cref="T:System.UriFormatException"><span data-ttu-id="230dd-132">Ausgelöst, wenn die Adresse nicht richtig formatiert ist.</span><span class="sxs-lookup"><span data-stu-id="230dd-132">Thrown when address is not correctly formed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (System.Collections.Generic.IEnumerable&lt;Uri&gt; addresses, Microsoft.Azure.NotificationHubs.NamespaceManagerSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; addresses, class Microsoft.Azure.NotificationHubs.NamespaceManagerSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.#ctor(System.Collections.Generic.IEnumerable{System.Uri},Microsoft.Azure.NotificationHubs.NamespaceManagerSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (addresses As IEnumerable(Of Uri), settings As NamespaceManagerSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.NamespaceManager : seq&lt;Uri&gt; * Microsoft.Azure.NotificationHubs.NamespaceManagerSettings -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="new Microsoft.Azure.NotificationHubs.NamespaceManager (addresses, settings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="settings" Type="Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" />
      </Parameters>
      <Docs>
        <param name="addresses"><span data-ttu-id="230dd-133">Der vollständige URI-Adressen des dienstnamespaces.</span><span class="sxs-lookup"><span data-stu-id="230dd-133">The full URI addresses of the service namespace.</span></span></param>
        <param name="settings"><span data-ttu-id="230dd-134">Ein <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" /> -Objekt, das enthält die <see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.Credential" /> und <see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.OperationTimeout" /> Eigenschaften.</span><span class="sxs-lookup"><span data-stu-id="230dd-134">A <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" /> object, which contains the <see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.Credential" /> and <see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.OperationTimeout" /> properties.</span></span></param>
        <summary><span data-ttu-id="230dd-135">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> Klasse mit dem angegebenen Dienst Namespace-URI-Basisadressen und Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="230dd-135">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> class with the given service namespace URI base addresses and settings.</span></span></summary>
        <remarks>
            <span data-ttu-id="230dd-136">Obwohl es nicht zulässig ist die Namespace-Adressen Pfade einschließt, können Sie die Anmeldeinformationen, die nur auf einige Unterebenen von Basisadressen Aktionen autorisiert angeben, d. h. es ist nicht erforderlich, dass die Anmeldeinformationen, die Sie angeben, auf der Basis-Adressen werden Self-Service</span><span class="sxs-lookup"><span data-stu-id="230dd-136">Even though it is not allowed to include paths in the namespace addresses, you can specify a credential that authorizes you to perform actions only on some sublevels off of the base addresses, i.e. it is not a must that the credentials you specify be to the base adresses itself</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="230dd-137">Wird ausgelöst, wenn Adressen oder Einstellungen ist null.</span><span class="sxs-lookup"><span data-stu-id="230dd-137">Thrown when addresses or settings is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="230dd-138">Ausgelöst, wenn die Liste der Adressen null oder leer ist.</span><span class="sxs-lookup"><span data-stu-id="230dd-138">Thrown when addresses list is null or empty.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (System.Collections.Generic.IEnumerable&lt;Uri&gt; addresses, Microsoft.Azure.NotificationHubs.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; addresses, class Microsoft.Azure.NotificationHubs.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.#ctor(System.Collections.Generic.IEnumerable{System.Uri},Microsoft.Azure.NotificationHubs.TokenProvider)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.NamespaceManager : seq&lt;Uri&gt; * Microsoft.Azure.NotificationHubs.TokenProvider -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="new Microsoft.Azure.NotificationHubs.NamespaceManager (addresses, tokenProvider)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="tokenProvider" Type="Microsoft.Azure.NotificationHubs.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="addresses"><span data-ttu-id="230dd-139">Der vollständige URI-Adressen des dienstnamespaces.</span><span class="sxs-lookup"><span data-stu-id="230dd-139">The full URI addresses of the service namespace.</span></span></param>
        <param name="tokenProvider"><span data-ttu-id="230dd-140">Der Sicherheitstokenanbieter.</span><span class="sxs-lookup"><span data-stu-id="230dd-140">The security token provider.</span></span></param>
        <summary><span data-ttu-id="230dd-141">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> Klasse mit dem angegebenen Dienst Namespace-URI-Basisadressen und Anbieter von Sicherheitstoken.</span><span class="sxs-lookup"><span data-stu-id="230dd-141">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> class with the given service namespace URI base addresses and token provider.</span></span></summary>
        <remarks>
            <span data-ttu-id="230dd-142">Obwohl es nicht zulässig ist die Namespace-Adressen Pfade einschließt, können Sie die Anmeldeinformationen, die nur auf einige Unterebenen von Basisadressen Aktionen autorisiert angeben, d. h. es ist nicht erforderlich, dass die Anmeldeinformationen, die Sie angeben, auf der Basis-Adressen werden Self-Service</span><span class="sxs-lookup"><span data-stu-id="230dd-142">Even though it is not allowed to include paths in the namespace addresses, you can specify a credential that authorizes you to perform actions only on some sublevels off of the base addresses, i.e. it is not a must that the credentials you specify be to the base adresses itself</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="230dd-143">Wird ausgelöst, wenn Adressen null ist.</span><span class="sxs-lookup"><span data-stu-id="230dd-143">Thrown if addresses is null.</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="230dd-144">Wird ausgelöst, wenn der Typ nicht um einen unterstützten Typ der Anmeldeinformationen ist.</span><span class="sxs-lookup"><span data-stu-id="230dd-144">Thrown when the type is not a supported Credential type.</span></span>
            <span data-ttu-id="230dd-145">Finden Sie unter <see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.TokenProvider" /> ausführliche Informationen zu den unterstützten Typen.</span><span class="sxs-lookup"><span data-stu-id="230dd-145">See <see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.TokenProvider" /> to know more about the supported types.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="230dd-146">Ausgelöst, wenn die Liste der Adressen null oder leer ist.</span><span class="sxs-lookup"><span data-stu-id="230dd-146">Thrown when addresses list is null or empty.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (string address, Microsoft.Azure.NotificationHubs.NamespaceManagerSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string address, class Microsoft.Azure.NotificationHubs.NamespaceManagerSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.#ctor(System.String,Microsoft.Azure.NotificationHubs.NamespaceManagerSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (address As String, settings As NamespaceManagerSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.NamespaceManager : string * Microsoft.Azure.NotificationHubs.NamespaceManagerSettings -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="new Microsoft.Azure.NotificationHubs.NamespaceManager (address, settings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
        <Parameter Name="settings" Type="Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="230dd-147">Die vollständige Adresse des dienstnamespaces.</span><span class="sxs-lookup"><span data-stu-id="230dd-147">The full address of the service namespace.</span></span></param>
        <param name="settings"><span data-ttu-id="230dd-148">Ein <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" /> -Objekt, das enthält die <see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.Credential" /> und <see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.OperationTimeout" /> Eigenschaften.</span><span class="sxs-lookup"><span data-stu-id="230dd-148">A <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" /> object, which contains the <see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.Credential" /> and <see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.OperationTimeout" /> properties.</span></span></param>
        <summary><span data-ttu-id="230dd-149">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> Klasse mit dem angegebenen Namespace dienstbasisadresse und <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="230dd-149">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> class with the given service namespace base address and <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" /> object.</span></span></summary>
        <remarks>
            <span data-ttu-id="230dd-150">Obwohl es nicht zulässig ist, Pfade in der Namespace-Adresse enthalten, können Sie die Anmeldeinformationen, die nur auf einige Unterebenen aus der Basisadresse Aktionen autorisiert angeben, d. h. es ist nicht erforderlich, die die Anmeldeinformationen, die Sie angeben, auf der Basis Adresse selbst sein</span><span class="sxs-lookup"><span data-stu-id="230dd-150">Even though it is not allowed to include paths in the namespace address, you can specify a credential that authorizes you to perform actions only on some sublevels off of the base address, i.e. it is not a must that the credentials you specify be to the base adress itself</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="230dd-151"><paramref name="address" /> oder <paramref name="settings" /> ist NULL.</span><span class="sxs-lookup"><span data-stu-id="230dd-151"><paramref name="address" /> or <paramref name="settings" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="230dd-152"><paramref name="address" />enthält einen Pfad an die vollständige Adresse des Dienstnamespace angefügt.</span><span class="sxs-lookup"><span data-stu-id="230dd-152"><paramref name="address" /> contains a path appended to the full address of the service namespace.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (string address, Microsoft.Azure.NotificationHubs.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string address, class Microsoft.Azure.NotificationHubs.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.#ctor(System.String,Microsoft.Azure.NotificationHubs.TokenProvider)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.NamespaceManager : string * Microsoft.Azure.NotificationHubs.TokenProvider -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="new Microsoft.Azure.NotificationHubs.NamespaceManager (address, tokenProvider)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
        <Parameter Name="tokenProvider" Type="Microsoft.Azure.NotificationHubs.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="230dd-153">Die vollständige Adresse des dienstnamespaces.</span><span class="sxs-lookup"><span data-stu-id="230dd-153">The full address of the service namespace.</span></span></param>
        <param name="tokenProvider"><span data-ttu-id="230dd-154">Der Sicherheitstokenanbieter.</span><span class="sxs-lookup"><span data-stu-id="230dd-154">The security token provider.</span></span></param>
        <summary><span data-ttu-id="230dd-155">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> Klasse mit dem angegebenen Namespace dienstbasisadresse und Anbieter von Sicherheitstoken.</span><span class="sxs-lookup"><span data-stu-id="230dd-155">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> class with the given service namespace base address and token provider.</span></span></summary>
        <remarks>
            <span data-ttu-id="230dd-156">Obwohl es nicht zulässig ist, Pfade in der Namespace-Adresse enthalten, können Sie Anmeldeinformationen angeben, die nur auf einige Unterebenen aus der Basisadresse Aktionen autorisiert.</span><span class="sxs-lookup"><span data-stu-id="230dd-156">Even though it is not allowed to include paths in the namespace address, you can specify a credential that authorizes you to perform actions only on some sublevels off of the base address.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="230dd-157"><paramref name="address" /> oder <paramref name="token provider" /> ist NULL.</span><span class="sxs-lookup"><span data-stu-id="230dd-157"><paramref name="address" /> or <paramref name="token provider" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="230dd-158"><paramref name="address" />enthält einen Pfad an die vollständige Adresse des Dienstnamespace angefügt.</span><span class="sxs-lookup"><span data-stu-id="230dd-158"><paramref name="address" /> contains a path appended to the full address of the service namespace.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (Uri address, Microsoft.Azure.NotificationHubs.NamespaceManagerSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri address, class Microsoft.Azure.NotificationHubs.NamespaceManagerSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.#ctor(System.Uri,Microsoft.Azure.NotificationHubs.NamespaceManagerSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (address As Uri, settings As NamespaceManagerSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.NamespaceManager : Uri * Microsoft.Azure.NotificationHubs.NamespaceManagerSettings -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="new Microsoft.Azure.NotificationHubs.NamespaceManager (address, settings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
        <Parameter Name="settings" Type="Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="230dd-159">Die vollständige URI-Adresse des dienstnamespaces.</span><span class="sxs-lookup"><span data-stu-id="230dd-159">The full URI address of the service namespace.</span></span></param>
        <param name="settings"><span data-ttu-id="230dd-160">Ein <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" /> -Objekt, das enthält die <see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.Credential" /> und <see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.OperationTimeout" /> Eigenschaften.</span><span class="sxs-lookup"><span data-stu-id="230dd-160">A <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" /> object, which contains the <see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.Credential" /> and <see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.OperationTimeout" /> properties.</span></span></param>
        <summary><span data-ttu-id="230dd-161">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> Klasse mit der angegebenen Service Namespace-URI-Basisadresse und <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="230dd-161">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> class with the given service namespace URI base address and <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" /> object.</span></span></summary>
        <remarks>
            <span data-ttu-id="230dd-162">Obwohl es nicht zulässig ist, Pfade in der Namespace-Adresse enthalten, können Sie die Anmeldeinformationen, die nur auf einige Unterebenen aus der Basisadresse Aktionen autorisiert angeben, d. h. es ist nicht erforderlich, die die Anmeldeinformationen, die Sie angeben, auf der Basis Adresse selbst sein</span><span class="sxs-lookup"><span data-stu-id="230dd-162">Even though it is not allowed to include paths in the namespace address, you can specify a credential that authorizes you to perform actions only on some sublevels off of the base address, i.e. it is not a must that the credentials you specify be to the base adress itself</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="230dd-163"><paramref name="address" /> oder <paramref name="settings" /> ist NULL.</span><span class="sxs-lookup"><span data-stu-id="230dd-163"><paramref name="address" /> or <paramref name="settings" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="230dd-164"><paramref name="address" />enthält einen Pfad an die vollständige Adresse des Dienstnamespace angefügt.</span><span class="sxs-lookup"><span data-stu-id="230dd-164"><paramref name="address" /> contains a path appended to the full address of the service namespace.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (Uri address, Microsoft.Azure.NotificationHubs.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri address, class Microsoft.Azure.NotificationHubs.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.#ctor(System.Uri,Microsoft.Azure.NotificationHubs.TokenProvider)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.NamespaceManager : Uri * Microsoft.Azure.NotificationHubs.TokenProvider -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="new Microsoft.Azure.NotificationHubs.NamespaceManager (address, tokenProvider)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
        <Parameter Name="tokenProvider" Type="Microsoft.Azure.NotificationHubs.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="230dd-165">Die vollständige URI-Adresse des dienstnamespaces.</span><span class="sxs-lookup"><span data-stu-id="230dd-165">The full URI address of the service namespace.</span></span></param>
        <param name="tokenProvider"><span data-ttu-id="230dd-166">Das Sicherheitsobjekt Tokenanbieter.</span><span class="sxs-lookup"><span data-stu-id="230dd-166">The security token provider object.</span></span></param>
        <summary><span data-ttu-id="230dd-167">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> Klasse mit der angegebenen Service Namespace-URI-Basisadresse und <see cref="T:Microsoft.Azure.NotificationHubs.TokenProvider" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="230dd-167">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> class with the given service namespace URI base address and <see cref="T:Microsoft.Azure.NotificationHubs.TokenProvider" /> object.</span></span></summary>
        <remarks>
            <span data-ttu-id="230dd-168">Obwohl es nicht zulässig ist, Pfade in der Namespace-Adresse enthalten, können Sie die Anmeldeinformationen, die nur auf einige Unterebenen aus der Basisadresse Aktionen autorisiert angeben, d. h. es ist nicht erforderlich, die die Anmeldeinformationen, die Sie angeben, auf der Basis Adresse selbst sein</span><span class="sxs-lookup"><span data-stu-id="230dd-168">Even though it is not allowed to include paths in the namespace address, you can specify a credential that authorizes you to perform actions only on some sublevels off of the base address, i.e. it is not a must that the credentials you specify be to the base adress itself</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="230dd-169"><paramref name="address" /> oder <paramref name="token provider" /> ist NULL.</span><span class="sxs-lookup"><span data-stu-id="230dd-169"><paramref name="address" /> or <paramref name="token provider" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="230dd-170">Wird ausgelöst, wenn der Typ nicht um einen unterstützten Typ der Anmeldeinformationen ist.</span><span class="sxs-lookup"><span data-stu-id="230dd-170">Thrown when the type is not a supported Credential type.</span></span>
            <span data-ttu-id="230dd-171">Finden Sie unter <see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.TokenProvider" /> ausführliche Informationen zu den unterstützten Typen.</span><span class="sxs-lookup"><span data-stu-id="230dd-171">See <see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.TokenProvider" /> to know more about the supported types.</span></span></exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="230dd-172"><paramref name="address" />enthält einen Pfad an die vollständige Adresse des Dienstnamespace angefügt.</span><span class="sxs-lookup"><span data-stu-id="230dd-172"><paramref name="address" /> contains a path appended to the full address of the service namespace.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Address">
      <MemberSignature Language="C#" Value="public Uri Address { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Address" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NamespaceManager.Address" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Address As Uri" />
      <MemberSignature Language="F#" Value="member this.Address : Uri" Usage="Microsoft.Azure.NotificationHubs.NamespaceManager.Address" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="230dd-173">Ruft die Basisadresse des Diensts-Namespace ab.</span><span class="sxs-lookup"><span data-stu-id="230dd-173">Gets the service namespace base address.</span></span></summary>
        <value><span data-ttu-id="230dd-174">Ein <see cref="T:System.Uri" /> , der die Basisadresse des Diensts Namespace darstellt.</span><span class="sxs-lookup"><span data-stu-id="230dd-174">A <see cref="T:System.Uri" /> that represents the service namespace base address.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetVersionInfo">
      <MemberSignature Language="C#" Value="public IAsyncResult BeginGetVersionInfo (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.IAsyncResult BeginGetVersionInfo(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.BeginGetVersionInfo(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function BeginGetVersionInfo (callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="member this.BeginGetVersionInfo : AsyncCallback * obj -&gt; IAsyncResult" Usage="namespaceManager.BeginGetVersionInfo (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback"><span data-ttu-id="230dd-175">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="230dd-175">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="230dd-176">Ein benutzerdefiniertes Objekt, das Statusinformationen über den asynchronen Vorgang enthält.</span><span class="sxs-lookup"><span data-stu-id="230dd-176">A user-defined object that contains state information about the asynchronous operation.</span></span> <span data-ttu-id="230dd-177">Dieses Objekt wird bei Abschluss des Vorgangs an den <see cref="M:Microsoft.Azure.NotificationHubs.NamespaceManager.EndGetVersioninfo(System.IAsyncResult)" />-Delegaten übergeben.</span><span class="sxs-lookup"><span data-stu-id="230dd-177">This object is passed to the <see cref="M:Microsoft.Azure.NotificationHubs.NamespaceManager.EndGetVersioninfo(System.IAsyncResult)" /> delegate when the operation is complete.</span></span></param>
        <summary><span data-ttu-id="230dd-178">Asynchrone Version von <see cref="M:Microsoft.Azure.NotificationHubs.NamespaceManager.GetVersionInfo(System.String)" /> Methode.</span><span class="sxs-lookup"><span data-stu-id="230dd-178">Asynchronous version of <see cref="M:Microsoft.Azure.NotificationHubs.NamespaceManager.GetVersionInfo(System.String)" /> method.</span></span></summary>
        <returns><span data-ttu-id="230dd-179">Ein <see cref="T:System.IAsyncResult" /> Objekt, das den asynchronen Vorgang zum Abrufen der Versionsinformationen verweist.</span><span class="sxs-lookup"><span data-stu-id="230dd-179">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous operation to get the version information.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.NamespaceManager Create ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.NamespaceManager Create() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.Create" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create () As NamespaceManager" />
      <MemberSignature Language="F#" Value="static member Create : unit -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="Microsoft.Azure.NotificationHubs.NamespaceManager.Create " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.NamespaceManager</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="230dd-180">Erstellt eine neue Instanz von <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" />.</span><span class="sxs-lookup"><span data-stu-id="230dd-180">Creates a new instance of <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" />.</span></span></summary>
        <returns><span data-ttu-id="230dd-181">Eine neue Instanz von <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" />.</span><span class="sxs-lookup"><span data-stu-id="230dd-181">A new instance of <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.NamespaceManager CreateFromConnectionString (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.NamespaceManager CreateFromConnectionString(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.CreateFromConnectionString(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String) As NamespaceManager" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="Microsoft.Azure.NotificationHubs.NamespaceManager.CreateFromConnectionString connectionString" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.NamespaceManager</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="230dd-182">Verbindung unkompliziert verwendet.</span><span class="sxs-lookup"><span data-stu-id="230dd-182">The connection sting used.</span></span></param>
        <summary><span data-ttu-id="230dd-183">Erstellt eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> mithilfe der angegebenen Verbindungszeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="230dd-183">Creates a new instance of <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> using a specified connection string.</span></span></summary>
        <returns><span data-ttu-id="230dd-184">Eine neue Instanz von <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" />.</span><span class="sxs-lookup"><span data-stu-id="230dd-184">A new instance of <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateNotificationHub">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.NotificationHubDescription CreateNotificationHub (Microsoft.Azure.NotificationHubs.NotificationHubDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.NotificationHubs.NotificationHubDescription CreateNotificationHub(class Microsoft.Azure.NotificationHubs.NotificationHubDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.CreateNotificationHub(Microsoft.Azure.NotificationHubs.NotificationHubDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateNotificationHub (description As NotificationHubDescription) As NotificationHubDescription" />
      <MemberSignature Language="F#" Value="member this.CreateNotificationHub : Microsoft.Azure.NotificationHubs.NotificationHubDescription -&gt; Microsoft.Azure.NotificationHubs.NotificationHubDescription" Usage="namespaceManager.CreateNotificationHub description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.NotificationHubDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.Azure.NotificationHubs.NotificationHubDescription" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="230dd-185">Das Beschreibungsobjekt für beschreiben die Attribute, mit denen der neue benachrichtigungshub erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="230dd-185">The description object describing the attributes with which the new notification hub will be created.</span></span></param>
        <summary><span data-ttu-id="230dd-186">Erstellt einen neuen benachrichtigungs-Hub mit den angegebenen Eigenschaften der <paramref name="description" /> Parameter.</span><span class="sxs-lookup"><span data-stu-id="230dd-186">Creates a new notification hub with the properties specified in the <paramref name="description" /> parameter.</span></span></summary>
        <returns><span data-ttu-id="230dd-187">Ein <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubDescription" /> Objekt mit der Beschreibung des neu erstellten benachrichtigungs-Hub.</span><span class="sxs-lookup"><span data-stu-id="230dd-187">A <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubDescription" /> object with the description of the newly created notification hub.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateNotificationHubAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt; CreateNotificationHubAsync (Microsoft.Azure.NotificationHubs.NotificationHubDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt; CreateNotificationHubAsync(class Microsoft.Azure.NotificationHubs.NotificationHubDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.CreateNotificationHubAsync(Microsoft.Azure.NotificationHubs.NotificationHubDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateNotificationHubAsync (description As NotificationHubDescription) As Task(Of NotificationHubDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateNotificationHubAsync : Microsoft.Azure.NotificationHubs.NotificationHubDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt;" Usage="namespaceManager.CreateNotificationHubAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.Azure.NotificationHubs.NotificationHubDescription" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="230dd-188">Das Beschreibungsobjekt für beschreiben die Attribute, mit denen der neue benachrichtigungshub erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="230dd-188">The description object describing the attributes with which the new notification hub will be created.</span></span></param>
        <summary><span data-ttu-id="230dd-189">Erstellt asynchron einen neuen benachrichtigungs-Hub mit den angegebenen Eigenschaften der <paramref name="description" /> Parameter.</span><span class="sxs-lookup"><span data-stu-id="230dd-189">Asynchronously creates a new notification hub with the properties specified in the <paramref name="description" /> parameter.</span></span></summary>
        <returns><span data-ttu-id="230dd-190">Ein <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubDescription" /> Objekt mit der Beschreibung des neu erstellten benachrichtigungs-Hub.</span><span class="sxs-lookup"><span data-stu-id="230dd-190">A <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubDescription" /> object with the description of the newly created notification hub.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteNotificationHub">
      <MemberSignature Language="C#" Value="public void DeleteNotificationHub (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteNotificationHub(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.DeleteNotificationHub(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteNotificationHub (path As String)" />
      <MemberSignature Language="F#" Value="member this.DeleteNotificationHub : string -&gt; unit" Usage="namespaceManager.DeleteNotificationHub path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="230dd-191">Der Pfad auf den Notification Hub.</span><span class="sxs-lookup"><span data-stu-id="230dd-191">The path to the notification hub.</span></span></param>
        <summary><span data-ttu-id="230dd-192">Löscht einen benachrichtigungs-Hub an der bereitgestellten <paramref name="path" />.</span><span class="sxs-lookup"><span data-stu-id="230dd-192">Deletes a notification hub at the provided <paramref name="path" />.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteNotificationHubAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteNotificationHubAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteNotificationHubAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.DeleteNotificationHubAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteNotificationHubAsync (path As String) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteNotificationHubAsync : string -&gt; System.Threading.Tasks.Task" Usage="namespaceManager.DeleteNotificationHubAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="230dd-193">Der Pfad auf den Notification Hub.</span><span class="sxs-lookup"><span data-stu-id="230dd-193">The path to the notification hub.</span></span></param>
        <summary><span data-ttu-id="230dd-194">Löscht asynchron einen benachrichtigungs-Hub an der bereitgestellten <paramref name="path" />.</span><span class="sxs-lookup"><span data-stu-id="230dd-194">Asynchronously deletes a notification hub at the provided <paramref name="path" />.</span></span></summary>
        <returns><span data-ttu-id="230dd-195">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="230dd-195">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndDeleteInstallation">
      <MemberSignature Language="C#" Value="public void EndDeleteInstallation (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void EndDeleteInstallation(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.EndDeleteInstallation(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Sub EndDeleteInstallation (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="member this.EndDeleteInstallation : IAsyncResult -&gt; unit" Usage="namespaceManager.EndDeleteInstallation result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="230dd-196">Der Verweis auf die ausstehende asynchrone Anforderung, die abgewartet werden soll.</span><span class="sxs-lookup"><span data-stu-id="230dd-196">The reference to the pending asynchronous request to wait for.</span></span></param>
        <summary>
            <span data-ttu-id="230dd-197">Wartet, bis zum Abschluss der Installation steht asynchronen Löschvorgang.</span><span class="sxs-lookup"><span data-stu-id="230dd-197">Waits for the pending asynchronous delete installation to complete.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndDeleteRegistration">
      <MemberSignature Language="C#" Value="public void EndDeleteRegistration (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void EndDeleteRegistration(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.EndDeleteRegistration(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Sub EndDeleteRegistration (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="member this.EndDeleteRegistration : IAsyncResult -&gt; unit" Usage="namespaceManager.EndDeleteRegistration result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="230dd-198">Ein <see cref="T:System.IAsyncResult" /> Objekt, das das Ergebnis des Löschvorgangs Registrierung darstellt.</span><span class="sxs-lookup"><span data-stu-id="230dd-198">An <see cref="T:System.IAsyncResult" /> object that represents the result of the registration deletion operation.</span></span></param>
        <summary><span data-ttu-id="230dd-199">Beendet eine asynchrone Anforderung, eine Registrierung zu löschen.</span><span class="sxs-lookup"><span data-stu-id="230dd-199">Ends an asynchronous request to delete a registration.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndGetVersionInfo">
      <MemberSignature Language="C#" Value="public string EndGetVersionInfo (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string EndGetVersionInfo(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.EndGetVersionInfo(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Function EndGetVersionInfo (result As IAsyncResult) As String" />
      <MemberSignature Language="F#" Value="member this.EndGetVersionInfo : IAsyncResult -&gt; string" Usage="namespaceManager.EndGetVersionInfo result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="230dd-200">Ein <see cref="T:System.IAsyncResult" /> Objekt, das das Ergebnis des Get-Versionsinformationen darstellt.</span><span class="sxs-lookup"><span data-stu-id="230dd-200">An <see cref="T:System.IAsyncResult" /> object that represents the result of the get version information.</span></span></param>
        <summary><span data-ttu-id="230dd-201">Beendet eine asynchrone Anforderung an die Versionsinformationen abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="230dd-201">Ends an asynchronous request to get version information.</span></span></summary>
        <returns><span data-ttu-id="230dd-202">Die Versionsinformationen.</span><span class="sxs-lookup"><span data-stu-id="230dd-202">The version information.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNotificationHub">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.NotificationHubDescription GetNotificationHub (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.NotificationHubs.NotificationHubDescription GetNotificationHub(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.GetNotificationHub(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNotificationHub (path As String) As NotificationHubDescription" />
      <MemberSignature Language="F#" Value="member this.GetNotificationHub : string -&gt; Microsoft.Azure.NotificationHubs.NotificationHubDescription" Usage="namespaceManager.GetNotificationHub path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.NotificationHubDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="230dd-203">Der Pfad auf den Dienstnamespace.</span><span class="sxs-lookup"><span data-stu-id="230dd-203">The path to the service namespace.</span></span></param>
        <summary><span data-ttu-id="230dd-204">Ruft die Beschreibung des benachrichtigungs-Hub aus dem Dienstnamespace ab.</span><span class="sxs-lookup"><span data-stu-id="230dd-204">Retrieves the description of a notification hub from the service namespace.</span></span></summary>
        <returns><span data-ttu-id="230dd-205">Die <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubDescription" /> aus dem Dienstnamespace.</span><span class="sxs-lookup"><span data-stu-id="230dd-205">The <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubDescription" /> from the service namespace.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNotificationHubAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt; GetNotificationHubAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt; GetNotificationHubAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.GetNotificationHubAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNotificationHubAsync (path As String) As Task(Of NotificationHubDescription)" />
      <MemberSignature Language="F#" Value="member this.GetNotificationHubAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt;" Usage="namespaceManager.GetNotificationHubAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="230dd-206">Der Pfad auf den Dienstnamespace.</span><span class="sxs-lookup"><span data-stu-id="230dd-206">The path to the service namespace.</span></span></param>
        <summary><span data-ttu-id="230dd-207">Ruft Sie die Beschreibung des benachrichtigungs-Hub asynchron aus dem Dienstnamespace ab.</span><span class="sxs-lookup"><span data-stu-id="230dd-207">Asynchronously retrieves the description of a notification hub from the service namespace.</span></span></summary>
        <returns><span data-ttu-id="230dd-208">Der asynchrone Vorgang, der die Beschreibung des benachrichtigungs-Hub von dienstnamespaces abruft.</span><span class="sxs-lookup"><span data-stu-id="230dd-208">The asynchronous operation that retrieves the description of a notification hub from the service namespace.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNotificationHubJobAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt; GetNotificationHubJobAsync (string jobId, string notificationHubPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationHubJob&gt; GetNotificationHubJobAsync(string jobId, string notificationHubPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.GetNotificationHubJobAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNotificationHubJobAsync (jobId As String, notificationHubPath As String) As Task(Of NotificationHubJob)" />
      <MemberSignature Language="F#" Value="member this.GetNotificationHubJobAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;" Usage="namespaceManager.GetNotificationHubJobAsync (jobId, notificationHubPath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="notificationHubPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="230dd-209">Die ID des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="230dd-209">The ID of the job.</span></span></param>
        <param name="notificationHubPath"><span data-ttu-id="230dd-210">Der Pfad auf den Notification Hub.</span><span class="sxs-lookup"><span data-stu-id="230dd-210">The path to the notification hub.</span></span></param>
        <summary><span data-ttu-id="230dd-211">Ruft asynchron eine angegebene Notification Hubs-Auftrag ab.</span><span class="sxs-lookup"><span data-stu-id="230dd-211">Asynchronously gets a specified notification hubs job.</span></span></summary>
        <returns><span data-ttu-id="230dd-212">Gibt <see cref="T:System.Threading.Tasks.Task`1" />zurück.</span><span class="sxs-lookup"><span data-stu-id="230dd-212">Returns <see cref="T:System.Threading.Tasks.Task`1" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNotificationHubJobsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;&gt; GetNotificationHubJobsAsync (string notificationHubPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;&gt; GetNotificationHubJobsAsync(string notificationHubPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.GetNotificationHubJobsAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNotificationHubJobsAsync (notificationHubPath As String) As Task(Of IEnumerable(Of NotificationHubJob))" />
      <MemberSignature Language="F#" Value="member this.GetNotificationHubJobsAsync : string -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;&gt;" Usage="namespaceManager.GetNotificationHubJobsAsync notificationHubPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="notificationHubPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="notificationHubPath"><span data-ttu-id="230dd-213">Der Pfad auf den Notification Hub.</span><span class="sxs-lookup"><span data-stu-id="230dd-213">The path to the notification hub.</span></span></param>
        <summary><span data-ttu-id="230dd-214">Asynchron Ruft einen Satz von alle Notification Hubs Aufträge ab.</span><span class="sxs-lookup"><span data-stu-id="230dd-214">Asynchronously gets a set of all notification hubs jobs.</span></span></summary>
        <returns><span data-ttu-id="230dd-215">Gibt <see cref="T:System.Threading.Tasks.Task`1" />zurück.</span><span class="sxs-lookup"><span data-stu-id="230dd-215">Returns <see cref="T:System.Threading.Tasks.Task`1" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNotificationHubs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt; GetNotificationHubs ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt; GetNotificationHubs() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.GetNotificationHubs" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNotificationHubs () As IEnumerable(Of NotificationHubDescription)" />
      <MemberSignature Language="F#" Value="member this.GetNotificationHubs : unit -&gt; seq&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt;" Usage="namespaceManager.GetNotificationHubs " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="230dd-216">Ruft die Beschreibung des benachrichtigungs-Hub aus dem Dienstnamespace ab.</span><span class="sxs-lookup"><span data-stu-id="230dd-216">Retrieves the description of a notification hub from the service namespace.</span></span></summary>
        <returns><span data-ttu-id="230dd-217">Die Liste der Beschreibung des benachrichtigungs-Hub aus dem Dienstnamespace.</span><span class="sxs-lookup"><span data-stu-id="230dd-217">The list of description of a notification hub from the service namespace.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNotificationHubsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt;&gt; GetNotificationHubsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt;&gt; GetNotificationHubsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.GetNotificationHubsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNotificationHubsAsync () As Task(Of IEnumerable(Of NotificationHubDescription))" />
      <MemberSignature Language="F#" Value="member this.GetNotificationHubsAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt;&gt;" Usage="namespaceManager.GetNotificationHubsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="230dd-218">Ruft Sie die Beschreibung des benachrichtigungs-Hub asynchron aus dem Dienstnamespace ab.</span><span class="sxs-lookup"><span data-stu-id="230dd-218">Asynchronously retrieves the description of a notification hub from the service namespace.</span></span></summary>
        <returns><span data-ttu-id="230dd-219">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="230dd-219">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVersionInfo">
      <MemberSignature Language="C#" Value="public string GetVersionInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetVersionInfo() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.GetVersionInfo" />
      <MemberSignature Language="VB.NET" Value="Public Function GetVersionInfo () As String" />
      <MemberSignature Language="F#" Value="member this.GetVersionInfo : unit -&gt; string" Usage="namespaceManager.GetVersionInfo " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="230dd-220">Ruft eine Zeichenfolge im Format "YYYY-MM", die die maximal unterstützte Protokollversion angibt, die den Server oder-Dienst verarbeiten kann.</span><span class="sxs-lookup"><span data-stu-id="230dd-220">Retrieves a string of the format "YYYY-MM" that indicates the maximum supported protocol version that the server or service can handle.</span></span></summary>
        <returns><span data-ttu-id="230dd-221">Eine Zeichenfolge, die maximal unterstützte Protokollversion angibt, die den Server oder-Dienst verarbeiten kann.</span><span class="sxs-lookup"><span data-stu-id="230dd-221">A string that indicates the maximum supported protocol version that the server or service can handle.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVersionInfoAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetVersionInfoAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; GetVersionInfoAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.GetVersionInfoAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetVersionInfoAsync () As Task(Of String)" />
      <MemberSignature Language="F#" Value="member this.GetVersionInfoAsync : unit -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="namespaceManager.GetVersionInfoAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="230dd-222">Asynchron Ruft eine Zeichenfolge im Format "YYYY-MM", die die maximal unterstützte Protokollversion angibt, die den Server oder-Dienst verarbeiten kann.</span><span class="sxs-lookup"><span data-stu-id="230dd-222">Asynchronously retrieves a string of the format "YYYY-MM" that indicates the maximum supported protocol version that the server or service can handle.</span></span></summary>
        <returns><span data-ttu-id="230dd-223">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="230dd-223">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NotificationHubExists">
      <MemberSignature Language="C#" Value="public bool NotificationHubExists (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool NotificationHubExists(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.NotificationHubExists(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function NotificationHubExists (path As String) As Boolean" />
      <MemberSignature Language="F#" Value="member this.NotificationHubExists : string -&gt; bool" Usage="namespaceManager.NotificationHubExists path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="230dd-224">Der Pfad auf den Notification Hub.</span><span class="sxs-lookup"><span data-stu-id="230dd-224">The path to the notification hub.</span></span></param>
        <summary><span data-ttu-id="230dd-225">Bestimmt, ob es ein benachrichtigungs-Hub an der angegebenen <paramref name="path" /> im Dienstnamespace.</span><span class="sxs-lookup"><span data-stu-id="230dd-225">Determines whether there is a notification hub at the specified <paramref name="path" /> in the service namespace.</span></span></summary>
        <returns><span data-ttu-id="230dd-226">True, wenn es ein benachrichtigungs-Hub an der angegebenen <paramref name="path" /> im Dienstnamespace; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="230dd-226">true if there is a notification hub at the specified <paramref name="path" /> in the service namespace; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NotificationHubExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; NotificationHubExistsAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;bool&gt; NotificationHubExistsAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.NotificationHubExistsAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function NotificationHubExistsAsync (path As String) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.NotificationHubExistsAsync : string -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="namespaceManager.NotificationHubExistsAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="230dd-227">Der Pfad auf den Notification Hub.</span><span class="sxs-lookup"><span data-stu-id="230dd-227">The path to the notification hub.</span></span></param>
        <summary><span data-ttu-id="230dd-228">Ermittelt asynchron, ob ein benachrichtigungs-Hub, an der angegebenen vorliegt <paramref name="path" /> im Dienstnamespace.</span><span class="sxs-lookup"><span data-stu-id="230dd-228">Asynchronously determines whether there is a notification hub at the specified <paramref name="path" /> in the service namespace.</span></span></summary>
        <returns><span data-ttu-id="230dd-229">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="230dd-229">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtocolVersion">
      <MemberSignature Language="C#" Value="public const string ProtocolVersion;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string ProtocolVersion" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.NamespaceManager.ProtocolVersion" />
      <MemberSignature Language="VB.NET" Value="Public Const ProtocolVersion As String " />
      <MemberSignature Language="F#" Value="val mutable ProtocolVersion : string" Usage="Microsoft.Azure.NotificationHubs.NamespaceManager.ProtocolVersion" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="230dd-230">Gibt die Zeichenfolge im Format "YYYY-MM", die der Client-Protokollversion angibt.</span><span class="sxs-lookup"><span data-stu-id="230dd-230">Specifies the string of the format "YYYY-MM" that indicates the client's protocol version.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Settings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.NamespaceManagerSettings Settings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.NotificationHubs.NamespaceManagerSettings Settings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NamespaceManager.Settings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Settings As NamespaceManagerSettings" />
      <MemberSignature Language="F#" Value="member this.Settings : Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" Usage="Microsoft.Azure.NotificationHubs.NamespaceManager.Settings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.NamespaceManagerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="230dd-231">Ruft den Namespace-Dienstclient Einstellungen ab.</span><span class="sxs-lookup"><span data-stu-id="230dd-231">Gets the service namespace client settings.</span></span></summary>
        <value><span data-ttu-id="230dd-232">Ein <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" /> Objekt, das die Clienteinstellungen des Dienst-Namespace darstellt.</span><span class="sxs-lookup"><span data-stu-id="230dd-232">A <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" /> object that represents the service namespace client settings.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitNotificationHubJobAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt; SubmitNotificationHubJobAsync (Microsoft.Azure.NotificationHubs.NotificationHubJob job, string notificationHubPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationHubJob&gt; SubmitNotificationHubJobAsync(class Microsoft.Azure.NotificationHubs.NotificationHubJob job, string notificationHubPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.SubmitNotificationHubJobAsync(Microsoft.Azure.NotificationHubs.NotificationHubJob,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SubmitNotificationHubJobAsync (job As NotificationHubJob, notificationHubPath As String) As Task(Of NotificationHubJob)" />
      <MemberSignature Language="F#" Value="member this.SubmitNotificationHubJobAsync : Microsoft.Azure.NotificationHubs.NotificationHubJob * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;" Usage="namespaceManager.SubmitNotificationHubJobAsync (job, notificationHubPath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="job" Type="Microsoft.Azure.NotificationHubs.NotificationHubJob" />
        <Parameter Name="notificationHubPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="job"><span data-ttu-id="230dd-233">Ein <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubJob" /> Objekt, das den Auftrag zum Übermitteln von darstellt.</span><span class="sxs-lookup"><span data-stu-id="230dd-233">A <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubJob" /> object representing the job to submit.</span></span></param>
        <param name="notificationHubPath"><span data-ttu-id="230dd-234">Der Pfad auf den Notification Hub.</span><span class="sxs-lookup"><span data-stu-id="230dd-234">The path to the notification hub.</span></span></param>
        <summary><span data-ttu-id="230dd-235">Sendet einen benachrichtigungs-Hub-Auftrag für die Verarbeitung an.</span><span class="sxs-lookup"><span data-stu-id="230dd-235">Submits a notification hub job for processing.</span></span></summary>
        <returns><span data-ttu-id="230dd-236">Gibt <see cref="T:System.Threading.Tasks.Task`1" />zurück.</span><span class="sxs-lookup"><span data-stu-id="230dd-236">Returns <see cref="T:System.Threading.Tasks.Task`1" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateNotificationHub">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.NotificationHubDescription UpdateNotificationHub (Microsoft.Azure.NotificationHubs.NotificationHubDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.NotificationHubs.NotificationHubDescription UpdateNotificationHub(class Microsoft.Azure.NotificationHubs.NotificationHubDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.UpdateNotificationHub(Microsoft.Azure.NotificationHubs.NotificationHubDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateNotificationHub (description As NotificationHubDescription) As NotificationHubDescription" />
      <MemberSignature Language="F#" Value="member this.UpdateNotificationHub : Microsoft.Azure.NotificationHubs.NotificationHubDescription -&gt; Microsoft.Azure.NotificationHubs.NotificationHubDescription" Usage="namespaceManager.UpdateNotificationHub description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.NotificationHubDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.Azure.NotificationHubs.NotificationHubDescription" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="230dd-237">Das Beschreibungsobjekt für beschreiben die Attribute, die mit denen benachrichtigungshub aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="230dd-237">The description object describing the attributes with which the notification hub will be updated.</span></span></param>
        <summary><span data-ttu-id="230dd-238">Aktualisiert einen vorhandenen benachrichtigungs-Hub an den im angegebenen Pfad die <paramref name="description" /> Parameter.</span><span class="sxs-lookup"><span data-stu-id="230dd-238">Updates an existing notification hub at the path specified in the <paramref name="description" /> parameter.</span></span> <span data-ttu-id="230dd-239">Alle Notification Hub-Eigenschaften werden überschrieben, mit denen angegeben wird, der <paramref name="description" /> Parameter.</span><span class="sxs-lookup"><span data-stu-id="230dd-239">All the notification hub properties are overwritten with the ones specified in the <paramref name="description" /> parameter.</span></span> </summary>
        <returns><span data-ttu-id="230dd-240">Ein <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubDescription" /> Objekt, das eine Beschreibung des aktualisierten benachrichtigungs-Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="230dd-240">A <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubDescription" /> object containing a description of the updated notification hub.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateNotificationHubAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt; UpdateNotificationHubAsync (Microsoft.Azure.NotificationHubs.NotificationHubDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt; UpdateNotificationHubAsync(class Microsoft.Azure.NotificationHubs.NotificationHubDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.UpdateNotificationHubAsync(Microsoft.Azure.NotificationHubs.NotificationHubDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateNotificationHubAsync (description As NotificationHubDescription) As Task(Of NotificationHubDescription)" />
      <MemberSignature Language="F#" Value="member this.UpdateNotificationHubAsync : Microsoft.Azure.NotificationHubs.NotificationHubDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt;" Usage="namespaceManager.UpdateNotificationHubAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.Azure.NotificationHubs.NotificationHubDescription" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="230dd-241">Das Beschreibungsobjekt für beschreiben die Attribute, die mit denen benachrichtigungshub aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="230dd-241">The description object describing the attributes with which the notification hub will be updated.</span></span></param>
        <summary><span data-ttu-id="230dd-242">Aktualisiert asynchron an den im angegebenen Pfad ein vorhandenen benachrichtigungs-Hub der <paramref name="description" /> Parameter.</span><span class="sxs-lookup"><span data-stu-id="230dd-242">Asynchronously updates an existing notification hub at the path specified in the <paramref name="description" /> parameter.</span></span> <span data-ttu-id="230dd-243">Alle Notification Hub-Eigenschaften werden überschrieben, mit denen angegeben wird, der <paramref name="description" /> Parameter.</span><span class="sxs-lookup"><span data-stu-id="230dd-243">All the notification hub properties are overwritten with the ones specified in the <paramref name="description" /> parameter.</span></span></summary>
        <returns><span data-ttu-id="230dd-244">Ein <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubDescription" /> Objekt, das eine Beschreibung des aktualisierten benachrichtigungs-Hub enthält.</span><span class="sxs-lookup"><span data-stu-id="230dd-244">A <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubDescription" /> object containing a description of the updated notification hub.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>