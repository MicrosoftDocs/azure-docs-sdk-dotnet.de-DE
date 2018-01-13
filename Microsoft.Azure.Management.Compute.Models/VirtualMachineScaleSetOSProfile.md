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
            Beschreibt eine virtuelle Maschine Skalierung Satz Betriebssystemprofil an.
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
            Initialisiert eine neue Instanz der VirtualMachineScaleSetOSProfile-Klasse.
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
        <param name="computerNamePrefix">Gibt das computernamenpräfix für alle virtuellen Computer in der Menge der Skala an. Computer-Namenspräfixe müssen zwischen 1 und 15 Zeichen lang sein.</param>
        <param name="adminUsername">Gibt den Namen des Administratorkontos an. &lt;Brasilien&gt;&lt;Br&gt; **nur-Windows-Einschränkung:** darf nicht mit enden "." &lt;Br&gt;&lt;Br&gt; **unzulässige Werte:** "Administrator", "Admin", "User", "Benutzer1", "test", "Benutzer2", "test1", "user3", "admin1", "1", "123", "a", "Actuser" , "Adm", "admin2", "Aspnet", "backup", "console", "David", "Guest", "John", "Besitzer", "Root", "Server", "Sql", "Unterstützung von", "support_388945a0", "Sys", "test2", "test3", "user4", "user5". &lt;Brasilien&gt;&lt;Br&gt; **Mindestlänge-(Linux):** 1 Zeichen &lt;Br&gt;&lt;Br&gt; **maximale Länge (Linux):** 64 Zeichen &lt;Br&gt;&lt;Br&gt; **maximale Länge (Windows):** 20 Zeichen &lt;Br&gt;&lt;Br&gt; &lt;li&gt; Root-Zugriff auf den Linux-VM, finden Sie unter [mithilfe der Root-Berechtigungen für virtuelle Linux-Computer in Azure](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-use-root-privileges?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json)&lt;Br&gt;&lt;li&gt; für eine Liste der integrierten Systembenutzer unter Linux, die in diesem Feld nicht verwendet werden sollte, finden Sie unter [Benutzernamen für Linux auf Azure auswählen](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-usernames?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json)</param>
        <param name="adminPassword">Gibt das Kennwort des Administratorkontos an. &lt;Brasilien&gt;&lt;Br&gt; **Mindestlänge-(Windows):** 8 Zeichen &lt;Br&gt;&lt;Br&gt; **Mindestlänge-(Linux): ** 6 Zeichen &lt;Br&gt;&lt;Br&gt; **maximale Länge (Windows):** 123 Zeichen &lt;Br&gt;&lt;Brasilien &gt; **Maximale Länge (Linux):** 72 Zeichen &lt;Br&gt;&lt;Br&gt; **komplexitätsvoraussetzungen:** 3 von 4 folgenden Bedingungen erfüllt werden müssen &lt;Br&gt; untere Zeichen hat &lt;Br&gt;oberen Zeichen &lt;Br&gt; verfügt über eine Ziffer &lt;Br&gt; verfügt über eine Sonderzeichen (Regex entsprechen [\W_]) &lt;Br&gt;&lt;Br&gt; **unzulässige Werte:** "abc@123", "P@$$w0rd", "P@ssw0rd","P@ssword123 ","Pa$ $Word","pass@word1","Password!","Password1","Password22","Iloveyou!"
            &lt;Brasilien&gt;&lt;Br&gt; durch Zurücksetzen des Kennworts, finden Sie unter [Zurücksetzen der Remotedesktop-Dienst oder die Anmeldekennwort in einer Windows-VM](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-reset-rdp?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json) &lt;Br&gt;&lt;Brasilien &gt; Das Stammkennwort zurücksetzen, finden Sie unter [Verwalten von Benutzern und SSH, und überprüfen oder Reparieren von Datenträger auf Azure Linux-virtuelle Computer die VMAccess-Erweiterung](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-using-vmaccess-extension?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json#reset-root-password)</param>
        <param name="customData">Gibt eine Base64-codierte Zeichenfolge benutzerdefinierter Daten an. Die Base64-codierte Zeichenfolge wird in ein binäres Array decodiert, das als Datei auf dem virtuellen Computer gespeichert wird. Die maximale Länge des binären Arrays beträgt 65535 Bytes. &lt;Brasilien&gt;&lt;Br&gt; Cloud Init für Ihren virtuellen Computer verwenden, finden Sie unter [eine Linux-VM während der Erstellung des anpassen mithilfe von Cloud-Initialisierung](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-using-cloud-init?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json)</param>
        <param name="windowsConfiguration">Gibt die Einstellungen des Windows-Betriebssystems auf dem virtuellen Computer an.</param>
        <param name="linuxConfiguration">Gibt die Einstellungen der Linux-Betriebssystem auf dem virtuellen Computer an. &lt;Brasilien&gt;&lt;Br&gt;eine Liste der unterstützten Linux-Distributionen, finden Sie unter [Linux auf Distributionen Azure-Endorsed](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-endorsed-distros?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json) &lt;Br&gt;&lt;Br&gt; Zum Ausführen von nicht-Distributionen finden Sie unter [Informationen zu Non-Endorsed Verteilungen](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-create-upload-generic?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json).</param>
        <param name="secrets">Gibt die Gruppe von Zertifikaten, die auf die virtuellen Computer in der Skalierungsgruppe installiert werden sollen.</param>
        <summary>
            Initialisiert eine neue Instanz der VirtualMachineScaleSetOSProfile-Klasse.
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
            Ruft ab oder legt gibt das Kennwort des Administratorkontos an.
            &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; **Mindestlänge-(Windows):** 8 Zeichen &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; **Mindestlänge-(Linux):** 6 Zeichen &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; **Maximale Länge (Windows):** 123 Zeichen &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; **Maximale Länge (Linux):** 72 Zeichen &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; **Komplexitätsvoraussetzungen:** 3 und 4 der folgenden Bedingungen erfüllt werden müssen &amp;Lt; Br&amp;Gt; Weist die niedrigere Zeichen &amp;Lt; Br&amp;Gt; Weist die obere Zeichen &amp;Lt; Br&amp;Gt; Eine Ziffer &amp;Lt; Br&amp;Gt; Ein Sonderzeichen (Regex entsprechen [\W_]) wurde &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; **Unzulässige Werte:** "abc@123", "P@$$w0rd", "P@ssw0rd","P@ssword123", "Pa$ $Word", "pass@word1", "Password!", "Password1", "Password22", "Iloveyou!"
            &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Das Kennwort zurücksetzen, finden Sie unter [Zurücksetzen der Remotedesktop-Dienst oder die Anmeldekennwort in einer Windows-VM](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-reset-rdp?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json) &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Das Stammkennwort zurücksetzen, finden Sie unter [Verwalten von Benutzern und SSH, und überprüfen oder Reparieren von Datenträger auf Azure Linux-virtuelle Computer die VMAccess-Erweiterung](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-using-vmaccess-extension?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json#reset-root-password)
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
            Ruft ab oder legt gibt den Namen des Administratorkontos an.
            &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; **Nur-Windows-Einschränkung:** darf nicht mit enden "." &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; **Unzulässige Werte:** "Administrator", "Admin", "User", "Benutzer1", "test", "Benutzer2", "test1", "user3", "admin1", "1", "123", "a", "Actuser", "Adm", "admin2", "Aspnet", "backup", "Console", "David", "Guest", "John", " Besitzer","Root","Server","Sql","Unterstützung von","support_388945a0","Sys","test2","test3","user4","user5".
            &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; **Mindestlänge-(Linux):** 1 Zeichen &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; **Maximale Länge (Linux):** 64 Zeichen &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; **Maximale Länge (Windows):** 20 Zeichen &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt;&amp; Lt; li&amp;Gt; Root-Zugriff auf den Linux-VM, finden Sie unter [mithilfe der Root-Berechtigungen für virtuelle Linux-Computer in Azure](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-use-root-privileges?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json)&amp;Lt; Br&amp;Gt;&amp; Lt; li&amp;Gt; Eine Liste der integrierten Systembenutzer unter Linux, die in diesem Feld nicht verwendet werden sollte, finden Sie unter [Benutzernamen für Linux auf Azure auswählen](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-usernames?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json)
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
            Ruft ab oder legt gibt das computernamenpräfix für alle virtuellen Computer in der Menge der Skala an. Computer-Namenspräfixe müssen zwischen 1 und 15 Zeichen lang sein.
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
            Ruft ab oder legt gibt eine Base64-codierte Zeichenfolge benutzerdefinierter Daten an. Die Base64-codierte Zeichenfolge wird in ein binäres Array decodiert, das als Datei auf dem virtuellen Computer gespeichert wird. Die maximale Länge des binären Arrays beträgt 65535 Bytes. &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Cloud-Init für Ihren virtuellen Computer verwenden, finden Sie unter [eine Linux-VM während der Erstellung des anpassen mithilfe von Cloud-Initialisierung](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-using-cloud-init?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json)
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
            Ruft ab oder legt gibt die Einstellungen der Linux-Betriebssystem auf dem virtuellen Computer an. &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Eine Liste der unterstützten Linux-Distributionen, finden Sie unter [Linux auf Distributionen Azure-Endorsed](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-endorsed-distros?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json) &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Zum Ausführen von nicht-Distributionen finden Sie unter [Informationen zu Non-Endorsed Verteilungen](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-create-upload-generic?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json).
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
            Ruft ab oder legt gibt an, der Zertifikate, die auf die virtuellen Computer in der Skalierungsgruppe installiert werden sollen.
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
            Ruft ab oder legt gibt die Einstellungen des Windows-Betriebssystems auf dem virtuellen Computer an.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>