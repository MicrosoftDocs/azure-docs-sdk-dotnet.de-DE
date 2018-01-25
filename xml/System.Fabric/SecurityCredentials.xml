<Type Name="SecurityCredentials" FullName="System.Fabric.SecurityCredentials">
  <TypeSignature Language="C#" Value="public abstract class SecurityCredentials" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit SecurityCredentials extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.SecurityCredentials" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class SecurityCredentials" />
  <TypeSignature Language="F#" Value="type SecurityCredentials = class" />
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
      <para><span data-ttu-id="5eec3-101">Eine abstrakte Basisklasse für Typen, die Anmeldeinformationen für die Sicherheit darstellen.</span><span class="sxs-lookup"><span data-stu-id="5eec3-101">An abstract base class for types that represent security credentials.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CredentialType">
      <MemberSignature Language="C#" Value="public System.Fabric.CredentialType CredentialType { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.CredentialType CredentialType" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.SecurityCredentials.CredentialType" />
      <MemberSignature Language="VB.NET" Value="Public Property CredentialType As CredentialType" />
      <MemberSignature Language="F#" Value="member this.CredentialType : System.Fabric.CredentialType with get, set" Usage="System.Fabric.SecurityCredentials.CredentialType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.CredentialType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="5eec3-102">Gibt den Typ der Sicherheitsanmeldeinformationen verwenden, um den Cluster – secure gültige Werte sind "none", "X509", "Windows".</span><span class="sxs-lookup"><span data-stu-id="5eec3-102">Indicates the type of security credentials to use in order to secure the cluster – valid values are "none", "x509", "Windows".</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="5eec3-103">Der Typ der Sicherheitsanmeldeinformationen verwenden, um den Cluster zu sichern.</span><span class="sxs-lookup"><span data-stu-id="5eec3-103">The type of security credentials to use in order to secure the cluster.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadFrom">
      <MemberSignature Language="C#" Value="public static System.Fabric.SecurityCredentials LoadFrom (System.Fabric.CodePackageActivationContext codePackageActivationContext, string configPackageName, string sectionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Fabric.SecurityCredentials LoadFrom(class System.Fabric.CodePackageActivationContext codePackageActivationContext, string configPackageName, string sectionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.SecurityCredentials.LoadFrom(System.Fabric.CodePackageActivationContext,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member LoadFrom : System.Fabric.CodePackageActivationContext * string * string -&gt; System.Fabric.SecurityCredentials" Usage="System.Fabric.SecurityCredentials.LoadFrom (codePackageActivationContext, configPackageName, sectionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.SecurityCredentials</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="codePackageActivationContext" Type="System.Fabric.CodePackageActivationContext" />
        <Parameter Name="configPackageName" Type="System.String" />
        <Parameter Name="sectionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="codePackageActivationContext">
          <para><span data-ttu-id="5eec3-104">Die aktuelle Codepaket-Aktivierungskontext <see cref="T:System.Fabric.CodePackageActivationContext" />.</span><span class="sxs-lookup"><span data-stu-id="5eec3-104">The current code package activation context <see cref="T:System.Fabric.CodePackageActivationContext" />.</span></span></para>
        </param>
        <param name="configPackageName">
          <para><span data-ttu-id="5eec3-105">Die aktuelle Konfiguration Paketname.</span><span class="sxs-lookup"><span data-stu-id="5eec3-105">The current configuration package name.</span></span></para>
        </param>
        <param name="sectionName">
          <para><span data-ttu-id="5eec3-106">Dem Abschnitt in der Konfigurationsdatei, die die Sicherheitseinstellungen definiert.</span><span class="sxs-lookup"><span data-stu-id="5eec3-106">The section within the configuration file that defines all the security settings.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="5eec3-107">Instanziieren <see cref="T:System.Fabric.SecurityCredentials" /> Objekt aus den Einstellungen für die Dienstkonfigurationsdatei</span><span class="sxs-lookup"><span data-stu-id="5eec3-107">Instantiate <see cref="T:System.Fabric.SecurityCredentials" /> object from service configuration settings file</span></span></para>
        </summary>
        <returns><span data-ttu-id="5eec3-108">Die Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="5eec3-108">The security credentials.</span></span></returns>
        <remarks>
          <para> <span data-ttu-id="5eec3-109">Einstellungen enthält die Konfigurationsdatei ("Settings.xml") innerhalb der Service-Konfigurationsordner sollten alle Sicherheitseinstellungen, die zum Erstellen erforderlich ist <see cref="T:System.Fabric.SecurityCredentials" /> Objekt, und übergeben Sie an die <see cref="M:System.Fabric.IStatefulServicePartition.CreateReplicator(System.Fabric.IStateProvider,System.Fabric.ReplicatorSettings)" /> Methode.</span><span class="sxs-lookup"><span data-stu-id="5eec3-109">The configuration settings file (settings.xml) within the service configuration folder should contain all the security settings that is needed to create <see cref="T:System.Fabric.SecurityCredentials" /> object and pass to the <see cref="M:System.Fabric.IStatefulServicePartition.CreateReplicator(System.Fabric.IStateProvider,System.Fabric.ReplicatorSettings)" /> method.</span></span>
            <span data-ttu-id="5eec3-110">In der Regel bleibt auf den dienstautor, lesen Sie die Datei "Settings.xml", analysieren Sie die Werte aus, und erstellen entsprechend der <see cref="T:System.Fabric.SecurityCredentials" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="5eec3-110">Typically, the onus is on the service author to read the settings.xml file, parse the values and appropriately construct the <see cref="T:System.Fabric.SecurityCredentials" /> object.</span></span></para>
          <para><span data-ttu-id="5eec3-111">Mit der aktuellen Hilfsmethode kann den oben aufgeführten Vorgang dienstautor umgangen werden.</span><span class="sxs-lookup"><span data-stu-id="5eec3-111">With the current helper method, the service author can bypass the above process.</span></span></para>
          <para><span data-ttu-id="5eec3-112">Es folgen die Namen der Parameter, die in der Dienstkonfiguration "settings.xml" von Windows Fabric, um die oben genannten Analyse automatisch erkannt werden bereitgestellt werden sollten:</span><span class="sxs-lookup"><span data-stu-id="5eec3-112">The following are the parameter names that should be provided in the service configuration "settings.xml", to be recognizable by windows fabric to perform the above parsing automatically:</span></span></para>
          <list type="number">
            <item>
              <description>
                <para><span data-ttu-id="5eec3-113">CredentialType – Typ der Anmeldeinformationen zum sicheren Kommunikationskanals mit: X509 (X509 zertifikatsanmeldeinformationen) oder Windows (Windows-Anmeldeinformationen, erfordert active Directory)</span><span class="sxs-lookup"><span data-stu-id="5eec3-113">CredentialType–type of credentials to use to secure communication channel: X509 (X509 certificate credentials) or Windows (Windows credentials, requires active directory)</span></span></para>
              </description>
            </item>
          </list>
          <para> <span data-ttu-id="5eec3-114">CredentialType = X509</span><span class="sxs-lookup"><span data-stu-id="5eec3-114">CredentialType=X509</span></span></para>
          <list type="number">
            <item>
              <description>
                <para><span data-ttu-id="5eec3-115">StoreLocation-Speicherort, um das Zertifikat zu suchen: CurrentUser oder LocalMachine</span><span class="sxs-lookup"><span data-stu-id="5eec3-115">StoreLocation-Store location to find the certificate: CurrentUser or LocalMachine</span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="5eec3-116">"StoreName"-Name des Zertifikatspeichers, in dem das Zertifikat gesucht werden sollen</span><span class="sxs-lookup"><span data-stu-id="5eec3-116">StoreName-name of the certificate store where the certificate should be searched</span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="5eec3-117">FindType-identifiziert den Typ des Werts, der im Parameter "findValue" gebotenen: FindBySubjectName oder FindByThumbPrint</span><span class="sxs-lookup"><span data-stu-id="5eec3-117">FindType-Identifies the type of value provided by in the FindValue parameter: FindBySubjectName or FindByThumbPrint</span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="5eec3-118">Ziel von "findValue" als Suchkriterium für die Suche nach dem Zertifikat</span><span class="sxs-lookup"><span data-stu-id="5eec3-118">FindValue-Search target for finding the certificate</span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="5eec3-119">AllowedCommonNames eine durch Trennzeichen getrennte Liste der allgemeinen Namen/DNS-Namen.</span><span class="sxs-lookup"><span data-stu-id="5eec3-119">AllowedCommonNames-A comma separated list of certificate common names/dns names.</span></span> <span data-ttu-id="5eec3-120">Diese Liste sollten alle Zertifikate, die von Replikatoren verwendet, es wird verwendet, um eingehende Zertifikat zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="5eec3-120">This list should include all certificates used by replicators, it is used to validate incoming certificate.</span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="5eec3-121">IssuerThumbprints eine kommagetrennte Liste der zertifikatfingerabdrücke Aussteller.</span><span class="sxs-lookup"><span data-stu-id="5eec3-121">IssuerThumbprints-A comma separated list of issuer certificate thumbprints.</span></span> <span data-ttu-id="5eec3-122">Wenn angegeben, wird das eingehende Zertifikat überprüft, wenn er durch einen der Einträge in der Liste, zusätzlich zur Überprüfung der Zertifikatkette ausgegeben wird.</span><span class="sxs-lookup"><span data-stu-id="5eec3-122">When specified, the incoming certificate is validated if it is issued by one of the entries in the list, in addition to chain validation.</span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="5eec3-123">RemoteCertThumbprints eine durch Trennzeichen getrennte Liste der zertifikatfingerabdrücke.</span><span class="sxs-lookup"><span data-stu-id="5eec3-123">RemoteCertThumbprints-A comma separated list of certificate thumbprints.</span></span> <span data-ttu-id="5eec3-124">Diese Liste sollten alle Zertifikate, die von Replikatoren verwendet, es wird verwendet, um eingehende Zertifikat zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="5eec3-124">This list should include all certificates used by replicators, it is used to validate incoming certificate.</span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="5eec3-125">ProtectionLevel – gibt an, wie die Daten geschützt: anmelden oder EncryptAndSign oder None.</span><span class="sxs-lookup"><span data-stu-id="5eec3-125">ProtectionLevel-Indicates how the data is protected: Sign or EncryptAndSign or None.</span></span></para>
              </description>
            </item>
          </list>
          <para> <span data-ttu-id="5eec3-126">CredentialType = Windows</span><span class="sxs-lookup"><span data-stu-id="5eec3-126">CredentialType=Windows</span></span></para>
          <list type="number">
            <item>
              <description>
                <para><span data-ttu-id="5eec3-127">ServicePrincipalName Service Principal Name, die für den Dienst registriert.</span><span class="sxs-lookup"><span data-stu-id="5eec3-127">ServicePrincipalName-Service Principal name registered for the service.</span></span> <span data-ttu-id="5eec3-128">Kann leer sein, wenn der Dienst/Akteur Hostprozesse als ein Computerkonto ausgeführt wird (z. B.: "NetworkService" usw. "LocalSystem".)</span><span class="sxs-lookup"><span data-stu-id="5eec3-128">Can be empty if the service/actor host processes runs as a machine account (e.g: NetworkService, LocalSystem etc.)</span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="5eec3-129">WindowsIdentities eine kommagetrennte Liste der Windows-Identitäten aller Service/Akteur Host Prozesse.</span><span class="sxs-lookup"><span data-stu-id="5eec3-129">WindowsIdentities-A comma separated list of windows identities of all service/actor host processes.</span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="5eec3-130">ProtectionLevel – gibt an, wie die Daten geschützt: anmelden oder EncryptAndSign oder None.</span><span class="sxs-lookup"><span data-stu-id="5eec3-130">ProtectionLevel-Indicates how the data is protected: Sign or EncryptAndSign or None.</span></span></para>
              </description>
            </item>
          </list>
          <para><span data-ttu-id="5eec3-131">X509 Ausschnitt Konfigurationsbeispiel</span><span class="sxs-lookup"><span data-stu-id="5eec3-131">X509 configuration snippet sample</span></span></para>
          <code>
            <span data-ttu-id="5eec3-132">&lt;Name des Abschnitts "SecurityConfig" =&gt; &lt;Parametername = "CredentialType" Value = "X509" /&gt; &lt;Parametername = "FindType" Value = "FindByThumbprint" /&gt; &lt;Parametername = " "FindValue""Wert =" 9D c9 06 b1 69 dc 4f af fd 16 97 Ac 78 1e 80 67 90 74 9 d 2f "/&gt; &lt;Parametername ="StoreLocation"Value ="LocalMachine"/&gt; &lt;Parametername ="StoreName"Value ="My"/ &lt; c9 &gt; &gt;  &lt;Parametername = "ProtectionLevel" Value = "EncryptAndSign" /&gt; &lt;Parametername = "AllowedCommonNames" Value="My-Test-SAN1-Alice,My-Test-SAN1-Bob" /&gt; &lt;/ Im Abschnitt&gt;</span><span class="sxs-lookup"><span data-stu-id="5eec3-132">&lt;Section Name="SecurityConfig"&gt; &lt;Parameter Name="CredentialType" Value="X509" /&gt; &lt;Parameter Name="FindType" Value="FindByThumbprint" /&gt; &lt;Parameter Name="FindValue" Value="9d c9 06 b1 69 dc 4f af fd 16 97 ac 78 1e 80 67 90 74 9d 2f" /&gt; &lt;Parameter Name="StoreLocation" Value="LocalMachine" /&gt; &lt;Parameter Name="StoreName" Value="My" /&gt; &lt;Parameter Name="ProtectionLevel" Value="EncryptAndSign" /&gt; &lt;Parameter Name="AllowedCommonNames" Value="My-Test-SAN1-Alice,My-Test-SAN1-Bob" /&gt; &lt;/Section&gt;</span></span>
              </code>
          <para><span data-ttu-id="5eec3-133">Codeausschnitt für die Windows-Konfiguration, Beispiel 1: der Dienst/Akteur-Hostprozesse als "NetworkService" oder "LocalSystem" ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="5eec3-133">Windows configuration snippet sample 1: all the service/actor host processes run as NetworkService or LocalSystem.</span></span></para>
          <code><span data-ttu-id="5eec3-134">&lt;Name des Abschnitts "SecurityConfig" =&gt; &lt;Parametername = "CredentialType" Value = "Windows" /&gt; &lt;Parametername = "ServicePrincipalName" Value = "" /&gt; &lt;!--dieses Computers Gruppe enthält alle Computer in einem Cluster –&gt; &lt;Parametername = "WindowsIdentities" Value = "Redmond\ClusterMachineGroup" /&gt; &lt;Parametername = "ProtectionLevel" Value = "EncryptAndSign "/&gt;  &lt; /Section&gt;</span><span class="sxs-lookup"><span data-stu-id="5eec3-134">&lt;Section Name="SecurityConfig"&gt; &lt;Parameter Name="CredentialType" Value="Windows" /&gt; &lt;Parameter Name="ServicePrincipalName" Value="" /&gt; &lt;!--This machine group contains all machines in a cluster--&gt; &lt;Parameter Name="WindowsIdentities" Value="redmond\ClusterMachineGroup" /&gt; &lt;Parameter Name="ProtectionLevel" Value="EncryptAndSign" /&gt; &lt;/Section&gt;</span></span></code>
          <para><span data-ttu-id="5eec3-135">Codeausschnitt für die Windows-Konfiguration, Beispiel 1: alle Service/Akteur Hostprozesse als gruppenverwaltete Dienstkonto ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="5eec3-135">Windows configuration snippet sample 1: all service/actor host processes run as a group managed service account.</span></span></para>
          <code><span data-ttu-id="5eec3-136">&lt;Name des Abschnitts "SecurityConfig" =&gt; &lt;Parametername = "CredentialType" Value = "Windows" /&gt; &lt;Parametername = "ServicePrincipalName" Value="servicefabric/cluster.microsoft.com" /&gt; &lt;– Alle Akteur-Dienst-Hostprozesse ausführende Redmond\GroupManagedServiceAccount--&gt; &lt;Parametername = "WindowsIdentities" Value = "Redmond\GroupManagedServiceAccount" /&gt; &lt;Parametername = "ProtectionLevel" Value = "EncryptAndSign" /&gt;  &lt; /Section&gt;</span><span class="sxs-lookup"><span data-stu-id="5eec3-136">&lt;Section Name="SecurityConfig"&gt; &lt;Parameter Name="CredentialType" Value="Windows" /&gt; &lt;Parameter Name="ServicePrincipalName" Value="servicefabric/cluster.microsoft.com" /&gt; &lt;--All actor/service host processes run as redmond\GroupManagedServiceAccount--&gt; &lt;Parameter Name="WindowsIdentities" Value="redmond\GroupManagedServiceAccount" /&gt; &lt;Parameter Name="ProtectionLevel" Value="EncryptAndSign" /&gt; &lt;/Section&gt;</span></span></code>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>