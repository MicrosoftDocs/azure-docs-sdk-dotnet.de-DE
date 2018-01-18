<Type Name="VirtualMachineScaleSetOSProfile" FullName="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile">
  <TypeSignature Language="C#" Value="public class VirtualMachineScaleSetOSProfile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineScaleSetOSProfile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineScaleSetOSProfile" />
  <TypeSignature Language="F#" Value="type VirtualMachineScaleSetOSProfile = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d4dc7-101">Beschreibt eine virtuelle Maschine Skalierung Satz Betriebssystemprofil an.</span><span class="sxs-lookup"><span data-stu-id="d4dc7-101">Describes a virtual machine scale set OS profile.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetOSProfile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d4dc7-102">Initialisiert eine neue Instanz der VirtualMachineScaleSetOSProfile-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d4dc7-102">Initializes a new instance of the VirtualMachineScaleSetOSProfile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetOSProfile (string computerNamePrefix = null, string adminUsername = null, string adminPassword = null, string customData = null, Microsoft.Azure.Management.Compute.Models.WindowsConfiguration windowsConfiguration = null, Microsoft.Azure.Management.Compute.Models.LinuxConfiguration linuxConfiguration = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VaultSecretGroup&gt; secrets = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string computerNamePrefix, string adminUsername, string adminPassword, string customData, class Microsoft.Azure.Management.Compute.Models.WindowsConfiguration windowsConfiguration, class Microsoft.Azure.Management.Compute.Models.LinuxConfiguration linuxConfiguration, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.VaultSecretGroup&gt; secrets) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile.#ctor(System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Compute.Models.WindowsConfiguration,Microsoft.Azure.Management.Compute.Models.LinuxConfiguration,System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Models.VaultSecretGroup})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile : string * string * string * string * Microsoft.Azure.Management.Compute.Models.WindowsConfiguration * Microsoft.Azure.Management.Compute.Models.LinuxConfiguration * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VaultSecretGroup&gt; -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile" Usage="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile (computerNamePrefix, adminUsername, adminPassword, customData, windowsConfiguration, linuxConfiguration, secrets)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="computerNamePrefix" Type="System.String" />
        <Parameter Name="adminUsername" Type="System.String" />
        <Parameter Name="adminPassword" Type="System.String" />
        <Parameter Name="customData" Type="System.String" />
        <Parameter Name="windowsConfiguration" Type="Microsoft.Azure.Management.Compute.Models.WindowsConfiguration" />
        <Parameter Name="linuxConfiguration" Type="Microsoft.Azure.Management.Compute.Models.LinuxConfiguration" />
        <Parameter Name="secrets" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VaultSecretGroup&gt;" />
      </Parameters>
      <Docs>
        <param name="computerNamePrefix"><span data-ttu-id="d4dc7-103">Gibt das computernamenpräfix für alle virtuellen Computer in der Menge der Skala an.</span><span class="sxs-lookup"><span data-stu-id="d4dc7-103">Specifies the computer name prefix for all of the virtual machines in the scale set.</span></span> <span data-ttu-id="d4dc7-104">Computer-Namenspräfixe müssen zwischen 1 und 15 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="d4dc7-104">Computer name prefixes must be 1 to 15 characters long.</span></span></param>
        <param name="adminUsername"><span data-ttu-id="d4dc7-105">Gibt den Namen des Administratorkontos an.</span><span class="sxs-lookup"><span data-stu-id="d4dc7-105">Specifies the name of the administrator account.</span></span> <span data-ttu-id="d4dc7-106">&lt;Brasilien&gt;&lt;Br&gt; **nur-Windows-Einschränkung:** darf nicht mit enden "." &lt;Br&gt;&lt;Br&gt; **unzulässige Werte:** "Administrator", "Admin", "User", "Benutzer1", "test", "Benutzer2", "test1", "user3", "admin1", "1", "123", "a", "Actuser" , "Adm", "admin2", "Aspnet", "backup", "console", "David", "Guest", "John", "Besitzer", "Root", "Server", "Sql", "Unterstützung von", "support_388945a0", "Sys", "test2", "test3", "user4", "user5".</span><span class="sxs-lookup"><span data-stu-id="d4dc7-106">&lt;br&gt;&lt;br&gt; **Windows-only restriction:** Cannot end in "." &lt;br&gt;&lt;br&gt; **Disallowed values:** "administrator", "admin", "user", "user1", "test", "user2", "test1", "user3", "admin1", "1", "123", "a", "actuser", "adm", "admin2", "aspnet", "backup", "console", "david", "guest", "john", "owner", "root", "server", "sql", "support", "support_388945a0", "sys", "test2", "test3", "user4", "user5".</span></span> <span data-ttu-id="d4dc7-107">&lt;Brasilien&gt;&lt;Br&gt; **Mindestlänge-(Linux):** 1 Zeichen &lt;Br&gt;&lt;Br&gt; **maximale Länge (Linux):** 64 Zeichen &lt;Br&gt;&lt;Br&gt; **maximale Länge (Windows):** 20 Zeichen &lt;Br&gt;&lt;Br&gt; &lt;li&gt; Root-Zugriff auf den Linux-VM, finden Sie unter [mithilfe der Root-Berechtigungen für virtuelle Linux-Computer in Azure](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-use-root-privileges?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json)&lt;Br&gt;&lt;li&gt; für eine Liste der integrierten Systembenutzer unter Linux, die in diesem Feld nicht verwendet werden sollte, finden Sie unter [Benutzernamen für Linux auf Azure auswählen](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-usernames?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json)</span><span class="sxs-lookup"><span data-stu-id="d4dc7-107">&lt;br&gt;&lt;br&gt; **Minimum-length (Linux):** 1  character &lt;br&gt;&lt;br&gt; **Max-length (Linux):** 64 characters &lt;br&gt;&lt;br&gt; **Max-length (Windows):** 20 characters &lt;br&gt;&lt;br&gt;&lt;li&gt; For root access to the Linux VM, see [Using root privileges on Linux virtual machines in Azure](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-use-root-privileges?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json)&lt;br&gt;&lt;li&gt; For a list of built-in system users on Linux that should not be used in this field, see [Selecting User Names for Linux on Azure](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-usernames?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json)</span></span></param>
        <param name="adminPassword"><span data-ttu-id="d4dc7-108">Gibt das Kennwort des Administratorkontos an.</span><span class="sxs-lookup"><span data-stu-id="d4dc7-108">Specifies the password of the administrator account.</span></span> <span data-ttu-id="d4dc7-109">&lt;Brasilien&gt;&lt;Br&gt; **Mindestlänge-(Windows):** 8 Zeichen &lt;Br&gt;&lt;Br&gt; **Mindestlänge-(Linux): ** 6 Zeichen &lt;Br&gt;&lt;Br&gt; **maximale Länge (Windows):** 123 Zeichen &lt;Br&gt;&lt;Brasilien &gt; **Maximale Länge (Linux):** 72 Zeichen &lt;Br&gt;&lt;Br&gt; **komplexitätsvoraussetzungen:** 3 von 4 folgenden Bedingungen erfüllt werden müssen &lt;Br&gt; untere Zeichen hat &lt;Br&gt;oberen Zeichen &lt;Br&gt; verfügt über eine Ziffer &lt;Br&gt; verfügt über eine Sonderzeichen (Regex entsprechen [\W_]) &lt;Br&gt;&lt;Br&gt; **unzulässige Werte:** "abc@123", "P@$$w0rd", "P@ssw0rd","P@ssword123 ","Pa$ $Word","pass@word1","Password!","Password1","Password22","Iloveyou!"</span><span class="sxs-lookup"><span data-stu-id="d4dc7-109">&lt;br&gt;&lt;br&gt; **Minimum-length (Windows):** 8 characters &lt;br&gt;&lt;br&gt; **Minimum-length (Linux):** 6 characters &lt;br&gt;&lt;br&gt; **Max-length (Windows):** 123 characters &lt;br&gt;&lt;br&gt; **Max-length (Linux):** 72 characters &lt;br&gt;&lt;br&gt; **Complexity requirements:** 3 out of 4 conditions below need to be fulfilled &lt;br&gt; Has lower characters &lt;br&gt;Has upper characters &lt;br&gt; Has a digit &lt;br&gt; Has a special character (Regex match [\W_]) &lt;br&gt;&lt;br&gt; **Disallowed values:** "abc@123", "P@$$w0rd", "P@ssw0rd", "P@ssword123", "Pa$$word", "pass@word1", "Password!", "Password1", "Password22", "iloveyou!"</span></span>
            <span data-ttu-id="d4dc7-110">&lt;Brasilien&gt;&lt;Br&gt; durch Zurücksetzen des Kennworts, finden Sie unter [Zurücksetzen der Remotedesktop-Dienst oder die Anmeldekennwort in einer Windows-VM](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-reset-rdp?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json) &lt;Br&gt;&lt;Brasilien &gt; Das Stammkennwort zurücksetzen, finden Sie unter [Verwalten von Benutzern und SSH, und überprüfen oder Reparieren von Datenträger auf Azure Linux-virtuelle Computer die VMAccess-Erweiterung](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-using-vmaccess-extension?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json#reset-root-password)</span><span class="sxs-lookup"><span data-stu-id="d4dc7-110">&lt;br&gt;&lt;br&gt; For resetting the password, see [How to reset the Remote Desktop service or its login password in a Windows VM](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-reset-rdp?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json) &lt;br&gt;&lt;br&gt; For resetting root password, see [Manage users, SSH, and check or repair disks on Azure Linux VMs using the VMAccess Extension](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-using-vmaccess-extension?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json#reset-root-password)</span></span></param>
        <param name="customData"><span data-ttu-id="d4dc7-111">Gibt eine Base64-codierte Zeichenfolge benutzerdefinierter Daten an.</span><span class="sxs-lookup"><span data-stu-id="d4dc7-111">Specifies a base-64 encoded string of custom data.</span></span> <span data-ttu-id="d4dc7-112">Die Base64-codierte Zeichenfolge wird in ein binäres Array decodiert, das als Datei auf dem virtuellen Computer gespeichert wird.</span><span class="sxs-lookup"><span data-stu-id="d4dc7-112">The base-64 encoded string is decoded to a binary array that is saved as a file on the Virtual Machine.</span></span> <span data-ttu-id="d4dc7-113">Die maximale Länge des binären Arrays beträgt 65535 Bytes.</span><span class="sxs-lookup"><span data-stu-id="d4dc7-113">The maximum length of the binary array is 65535 bytes.</span></span> <span data-ttu-id="d4dc7-114">&lt;Brasilien&gt;&lt;Br&gt; Cloud Init für Ihren virtuellen Computer verwenden, finden Sie unter [eine Linux-VM während der Erstellung des anpassen mithilfe von Cloud-Initialisierung](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-using-cloud-init?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json)</span><span class="sxs-lookup"><span data-stu-id="d4dc7-114">&lt;br&gt;&lt;br&gt; For using cloud-init for your VM, see [Using cloud-init to customize a Linux VM during creation](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-using-cloud-init?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json)</span></span></param>
        <param name="windowsConfiguration"><span data-ttu-id="d4dc7-115">Gibt die Einstellungen des Windows-Betriebssystems auf dem virtuellen Computer an.</span><span class="sxs-lookup"><span data-stu-id="d4dc7-115">Specifies Windows operating system settings on the virtual machine.</span></span></param>
        <param name="linuxConfiguration"><span data-ttu-id="d4dc7-116">Gibt die Einstellungen der Linux-Betriebssystem auf dem virtuellen Computer an.</span><span class="sxs-lookup"><span data-stu-id="d4dc7-116">Specifies the Linux operating system settings on the virtual machine.</span></span> <span data-ttu-id="d4dc7-117">&lt;Brasilien&gt;&lt;Br&gt;eine Liste der unterstützten Linux-Distributionen, finden Sie unter [Linux auf Distributionen Azure-Endorsed](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-endorsed-distros?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json) &lt;Br&gt;&lt;Br&gt; Zum Ausführen von nicht-Distributionen finden Sie unter [Informationen zu Non-Endorsed Verteilungen](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-create-upload-generic?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json).</span><span class="sxs-lookup"><span data-stu-id="d4dc7-117">&lt;br&gt;&lt;br&gt;For a list of supported Linux distributions, see [Linux on Azure-Endorsed Distributions](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-endorsed-distros?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json) &lt;br&gt;&lt;br&gt; For running non-endorsed distributions, see [Information for Non-Endorsed Distributions](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-create-upload-generic?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json).</span></span></param>
        <param name="secrets"><span data-ttu-id="d4dc7-118">Gibt die Gruppe von Zertifikaten, die auf die virtuellen Computer in der Skalierungsgruppe installiert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="d4dc7-118">Specifies set of certificates that should be installed onto the virtual machines in the scale set.</span></span></param>
        <summary>
            <span data-ttu-id="d4dc7-119">Initialisiert eine neue Instanz der VirtualMachineScaleSetOSProfile-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d4dc7-119">Initializes a new instance of the VirtualMachineScaleSetOSProfile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdminPassword">
      <MemberSignature Language="C#" Value="public string AdminPassword { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AdminPassword" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile.AdminPassword" />
      <MemberSignature Language="VB.NET" Value="Public Property AdminPassword As String" />
      <MemberSignature Language="F#" Value="member this.AdminPassword : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile.AdminPassword" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="adminPassword")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d4dc7-120">Ruft ab oder legt gibt das Kennwort des Administratorkontos an.</span><span class="sxs-lookup"><span data-stu-id="d4dc7-120">Gets or sets specifies the password of the administrator account.</span></span>
            <span data-ttu-id="d4dc7-121">&amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; **Mindestlänge-(Windows):** 8 Zeichen &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; **Mindestlänge-(Linux):** 6 Zeichen &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; **Maximale Länge (Windows):** 123 Zeichen &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; **Maximale Länge (Linux):** 72 Zeichen &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; **Komplexitätsvoraussetzungen:** 3 und 4 der folgenden Bedingungen erfüllt werden müssen &amp;Lt; Br&amp;Gt; Weist die niedrigere Zeichen &amp;Lt; Br&amp;Gt; Weist die obere Zeichen &amp;Lt; Br&amp;Gt; Eine Ziffer &amp;Lt; Br&amp;Gt; Ein Sonderzeichen (Regex entsprechen [\W_]) wurde &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; **Unzulässige Werte:** "abc@123", "P@$$w0rd", "P@ssw0rd","P@ssword123", "Pa$ $Word", "pass@word1", "Password!", "Password1", "Password22", "Iloveyou!"</span><span class="sxs-lookup"><span data-stu-id="d4dc7-121">&amp;lt;br&amp;gt;&amp;lt;br&amp;gt; **Minimum-length (Windows):** 8 characters &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; **Minimum-length (Linux):** 6 characters &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; **Max-length (Windows):** 123 characters &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; **Max-length (Linux):** 72 characters &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; **Complexity requirements:** 3 out of 4 conditions below need to be fulfilled &amp;lt;br&amp;gt; Has lower characters &amp;lt;br&amp;gt;Has upper characters &amp;lt;br&amp;gt; Has a digit &amp;lt;br&amp;gt; Has a special character (Regex match [\W_]) &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; **Disallowed values:** "abc@123", "P@$$w0rd", "P@ssw0rd", "P@ssword123", "Pa$$word", "pass@word1", "Password!", "Password1", "Password22", "iloveyou!"</span></span>
            <span data-ttu-id="d4dc7-122">&amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Das Kennwort zurücksetzen, finden Sie unter [Zurücksetzen der Remotedesktop-Dienst oder die Anmeldekennwort in einer Windows-VM](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-reset-rdp?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json) &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Das Stammkennwort zurücksetzen, finden Sie unter [Verwalten von Benutzern und SSH, und überprüfen oder Reparieren von Datenträger auf Azure Linux-virtuelle Computer die VMAccess-Erweiterung](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-using-vmaccess-extension?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json#reset-root-password)</span><span class="sxs-lookup"><span data-stu-id="d4dc7-122">&amp;lt;br&amp;gt;&amp;lt;br&amp;gt; For resetting the password, see [How to reset the Remote Desktop service or its login password in a Windows VM](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-reset-rdp?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json) &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; For resetting root password, see [Manage users, SSH, and check or repair disks on Azure Linux VMs using the VMAccess Extension](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-using-vmaccess-extension?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json#reset-root-password)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdminUsername">
      <MemberSignature Language="C#" Value="public string AdminUsername { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AdminUsername" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile.AdminUsername" />
      <MemberSignature Language="VB.NET" Value="Public Property AdminUsername As String" />
      <MemberSignature Language="F#" Value="member this.AdminUsername : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile.AdminUsername" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="adminUsername")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d4dc7-123">Ruft ab oder legt gibt den Namen des Administratorkontos an.</span><span class="sxs-lookup"><span data-stu-id="d4dc7-123">Gets or sets specifies the name of the administrator account.</span></span>
            <span data-ttu-id="d4dc7-124">&amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; **Nur-Windows-Einschränkung:** darf nicht mit enden "." &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; **Unzulässige Werte:** "Administrator", "Admin", "User", "Benutzer1", "test", "Benutzer2", "test1", "user3", "admin1", "1", "123", "a", "Actuser", "Adm", "admin2", "Aspnet", "backup", "Console", "David", "Guest", "John", " Besitzer","Root","Server","Sql","Unterstützung von","support_388945a0","Sys","test2","test3","user4","user5".</span><span class="sxs-lookup"><span data-stu-id="d4dc7-124">&amp;lt;br&amp;gt;&amp;lt;br&amp;gt; **Windows-only restriction:** Cannot end in "." &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; **Disallowed values:** "administrator", "admin", "user", "user1", "test", "user2", "test1", "user3", "admin1", "1", "123", "a", "actuser", "adm", "admin2", "aspnet", "backup", "console", "david", "guest", "john", "owner", "root", "server", "sql", "support", "support_388945a0", "sys", "test2", "test3", "user4", "user5".</span></span>
            <span data-ttu-id="d4dc7-125">&amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; **Mindestlänge-(Linux):** 1 Zeichen &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; **Maximale Länge (Linux):** 64 Zeichen &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; **Maximale Länge (Windows):** 20 Zeichen &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt;&amp; Lt; li&amp;Gt; Root-Zugriff auf den Linux-VM, finden Sie unter [mithilfe der Root-Berechtigungen für virtuelle Linux-Computer in Azure](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-use-root-privileges?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json)&amp;Lt; Br&amp;Gt;&amp; Lt; li&amp;Gt; Eine Liste der integrierten Systembenutzer unter Linux, die in diesem Feld nicht verwendet werden sollte, finden Sie unter [Benutzernamen für Linux auf Azure auswählen](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-usernames?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json)</span><span class="sxs-lookup"><span data-stu-id="d4dc7-125">&amp;lt;br&amp;gt;&amp;lt;br&amp;gt; **Minimum-length (Linux):** 1 character &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; **Max-length (Linux):** 64 characters &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; **Max-length (Windows):** 20 characters &amp;lt;br&amp;gt;&amp;lt;br&amp;gt;&amp;lt;li&amp;gt; For root access to the Linux VM, see [Using root privileges on Linux virtual machines in Azure](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-use-root-privileges?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json)&amp;lt;br&amp;gt;&amp;lt;li&amp;gt; For a list of built-in system users on Linux that should not be used in this field, see [Selecting User Names for Linux on Azure](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-usernames?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComputerNamePrefix">
      <MemberSignature Language="C#" Value="public string ComputerNamePrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ComputerNamePrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile.ComputerNamePrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property ComputerNamePrefix As String" />
      <MemberSignature Language="F#" Value="member this.ComputerNamePrefix : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile.ComputerNamePrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="computerNamePrefix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d4dc7-126">Ruft ab oder legt gibt das computernamenpräfix für alle virtuellen Computer in der Menge der Skala an.</span><span class="sxs-lookup"><span data-stu-id="d4dc7-126">Gets or sets specifies the computer name prefix for all of the virtual machines in the scale set.</span></span> <span data-ttu-id="d4dc7-127">Computer-Namenspräfixe müssen zwischen 1 und 15 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="d4dc7-127">Computer name prefixes must be 1 to 15 characters long.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomData">
      <MemberSignature Language="C#" Value="public string CustomData { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CustomData" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile.CustomData" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomData As String" />
      <MemberSignature Language="F#" Value="member this.CustomData : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile.CustomData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="customData")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d4dc7-128">Ruft ab oder legt gibt eine Base64-codierte Zeichenfolge benutzerdefinierter Daten an.</span><span class="sxs-lookup"><span data-stu-id="d4dc7-128">Gets or sets specifies a base-64 encoded string of custom data.</span></span> <span data-ttu-id="d4dc7-129">Die Base64-codierte Zeichenfolge wird in ein binäres Array decodiert, das als Datei auf dem virtuellen Computer gespeichert wird.</span><span class="sxs-lookup"><span data-stu-id="d4dc7-129">The base-64 encoded string is decoded to a binary array that is saved as a file on the Virtual Machine.</span></span> <span data-ttu-id="d4dc7-130">Die maximale Länge des binären Arrays beträgt 65535 Bytes.</span><span class="sxs-lookup"><span data-stu-id="d4dc7-130">The maximum length of the binary array is 65535 bytes.</span></span> <span data-ttu-id="d4dc7-131">&amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Cloud-Init für Ihren virtuellen Computer verwenden, finden Sie unter [eine Linux-VM während der Erstellung des anpassen mithilfe von Cloud-Initialisierung](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-using-cloud-init?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json)</span><span class="sxs-lookup"><span data-stu-id="d4dc7-131">&amp;lt;br&amp;gt;&amp;lt;br&amp;gt; For using cloud-init for your VM, see [Using cloud-init to customize a Linux VM during creation](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-using-cloud-init?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LinuxConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.LinuxConfiguration LinuxConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.LinuxConfiguration LinuxConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile.LinuxConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property LinuxConfiguration As LinuxConfiguration" />
      <MemberSignature Language="F#" Value="member this.LinuxConfiguration : Microsoft.Azure.Management.Compute.Models.LinuxConfiguration with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile.LinuxConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="linuxConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.LinuxConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d4dc7-132">Ruft ab oder legt gibt die Einstellungen der Linux-Betriebssystem auf dem virtuellen Computer an.</span><span class="sxs-lookup"><span data-stu-id="d4dc7-132">Gets or sets specifies the Linux operating system settings on the virtual machine.</span></span> <span data-ttu-id="d4dc7-133">&amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Eine Liste der unterstützten Linux-Distributionen, finden Sie unter [Linux auf Distributionen Azure-Endorsed](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-endorsed-distros?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json) &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Zum Ausführen von nicht-Distributionen finden Sie unter [Informationen zu Non-Endorsed Verteilungen](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-create-upload-generic?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json).</span><span class="sxs-lookup"><span data-stu-id="d4dc7-133">&amp;lt;br&amp;gt;&amp;lt;br&amp;gt;For a list of supported Linux distributions, see [Linux on Azure-Endorsed Distributions](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-endorsed-distros?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json) &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; For running non-endorsed distributions, see [Information for Non-Endorsed Distributions](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-create-upload-generic?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Secrets">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VaultSecretGroup&gt; Secrets { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.VaultSecretGroup&gt; Secrets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile.Secrets" />
      <MemberSignature Language="VB.NET" Value="Public Property Secrets As IList(Of VaultSecretGroup)" />
      <MemberSignature Language="F#" Value="member this.Secrets : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VaultSecretGroup&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile.Secrets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="secrets")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VaultSecretGroup&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d4dc7-134">Ruft ab oder legt gibt an, der Zertifikate, die auf die virtuellen Computer in der Skalierungsgruppe installiert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="d4dc7-134">Gets or sets specifies set of certificates that should be installed onto the virtual machines in the scale set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WindowsConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.WindowsConfiguration WindowsConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.WindowsConfiguration WindowsConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile.WindowsConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property WindowsConfiguration As WindowsConfiguration" />
      <MemberSignature Language="F#" Value="member this.WindowsConfiguration : Microsoft.Azure.Management.Compute.Models.WindowsConfiguration with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile.WindowsConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="windowsConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.WindowsConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d4dc7-135">Ruft ab oder legt gibt die Einstellungen des Windows-Betriebssystems auf dem virtuellen Computer an.</span><span class="sxs-lookup"><span data-stu-id="d4dc7-135">Gets or sets specifies Windows operating system settings on the virtual machine.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>