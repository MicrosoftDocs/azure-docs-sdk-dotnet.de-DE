<Type Name="ConfigurationProperty" FullName="System.Fabric.Description.ConfigurationProperty">
  <TypeSignature Language="C#" Value="public sealed class ConfigurationProperty" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ConfigurationProperty extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ConfigurationProperty" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ConfigurationProperty" />
  <TypeSignature Language="F#" Value="type ConfigurationProperty = class" />
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
      <para><span data-ttu-id="bc48a-101">Gibt eine Konfigurationseinstellung und ihren Wert, der verwendet werden kann, um einen Dienst oder Anwendung konfigurieren.</span><span class="sxs-lookup"><span data-stu-id="bc48a-101">Specifies a configuration setting and its value that can be used to configure a service or application.</span></span></para>
      <para><span data-ttu-id="bc48a-102">Die Einstellungen werden in der Datei "Settings.xml" in das Manifest angegeben.</span><span class="sxs-lookup"><span data-stu-id="bc48a-102">The settings are specified in the settings.xml file in the service manifest.</span></span> <span data-ttu-id="bc48a-103">Weitere Informationen finden Sie unter https://docs.microsoft.com/azure/service-fabric/service-fabric-application-model</span><span class="sxs-lookup"><span data-stu-id="bc48a-103">For more information see https://docs.microsoft.com/azure/service-fabric/service-fabric-application-model</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DecryptValue">
      <MemberSignature Language="C#" Value="public System.Security.SecureString DecryptValue ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Security.SecureString DecryptValue() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ConfigurationProperty.DecryptValue" />
      <MemberSignature Language="VB.NET" Value="Public Function DecryptValue () As SecureString" />
      <MemberSignature Language="F#" Value="member this.DecryptValue : unit -&gt; System.Security.SecureString" Usage="configurationProperty.DecryptValue " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Security.SecureString</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="bc48a-104">Entschlüsselt einen verschlüsselten Wert und wird als SecureString zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="bc48a-104">Decrypts an encrypted value and returns it as a SecureString.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="bc48a-105">Gibt <see cref="T:System.Security.SecureString" />zurück.</span><span class="sxs-lookup"><span data-stu-id="bc48a-105">Returns <see cref="T:System.Security.SecureString" />.</span></span></para>
        </returns>
        <remarks><span data-ttu-id="bc48a-106">Finden Sie unter https://docs.microsoft.com/azure/service-fabric/service-fabric-application-secret-management ein Beispiel, wie Sie einen geheimen Schlüssel zu verschlüsseln und in der Konfiguration zu speichern und wie Sie mithilfe dieser Methode um den Wert zur Laufzeit zu entschlüsseln.</span><span class="sxs-lookup"><span data-stu-id="bc48a-106">See https://docs.microsoft.com/azure/service-fabric/service-fabric-application-secret-management for an example on how to encrypt a secret and store it in the configuration and how to use this method to decrypt the value at runtime.</span></span></remarks>
        <exception cref="T:System.InvalidOperationException">
          <para><span data-ttu-id="bc48a-107">Der Wert, der die <see cref="T:System.Fabric.Description.ConfigurationProperty" /> werden nicht verschlüsselt.</span><span class="sxs-lookup"><span data-stu-id="bc48a-107">The value of the <see cref="T:System.Fabric.Description.ConfigurationProperty" /> is not encrypted.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="IsEncrypted">
      <MemberSignature Language="C#" Value="public bool IsEncrypted { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsEncrypted" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ConfigurationProperty.IsEncrypted" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsEncrypted As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsEncrypted : bool" Usage="System.Fabric.Description.ConfigurationProperty.IsEncrypted" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="bc48a-108">Ruft ein Flag, das angibt, ob die Konfiguration verschlüsselt ist.</span><span class="sxs-lookup"><span data-stu-id="bc48a-108">Gets a flag indicating whether the configuration is encrypted.</span></span> </para>
        </summary>
        <value>
          <para><span data-ttu-id="bc48a-109">Gibt "true" zurück, wenn die Konfiguration verschlüsselt wird; "false", andernfalls.</span><span class="sxs-lookup"><span data-stu-id="bc48a-109">Returns true if the configuration is encrypted; false, otherwise.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MustOverride">
      <MemberSignature Language="C#" Value="public bool MustOverride { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool MustOverride" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ConfigurationProperty.MustOverride" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MustOverride As Boolean" />
      <MemberSignature Language="F#" Value="member this.MustOverride : bool" Usage="System.Fabric.Description.ConfigurationProperty.MustOverride" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="bc48a-110">Ruft ein Flag, das angibt, ob die Einstellung im Anwendungsmanifest außer Kraft gesetzt werden muss.</span><span class="sxs-lookup"><span data-stu-id="bc48a-110">Gets a flag indicating whether the setting must be overridden in the application manifest.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="bc48a-111">Flag, das angibt, ob die Einstellung im Anwendungsmanifest außer Kraft gesetzt werden muss.</span><span class="sxs-lookup"><span data-stu-id="bc48a-111">Flag indicating whether the setting must be overridden in the application manifest.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ConfigurationProperty.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="System.Fabric.Description.ConfigurationProperty.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="bc48a-112">Ruft den Namen der Einstellung entsprechend den Angaben in der Datei "Settings.xml" in das Manifest ab.</span><span class="sxs-lookup"><span data-stu-id="bc48a-112">Gets the name of the setting as specified in the settings.xml file in the service manifest.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="bc48a-113">Der Name der Einstellung.</span><span class="sxs-lookup"><span data-stu-id="bc48a-113">The name of the setting.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public string Value { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Value" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ConfigurationProperty.Value" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Value As String" />
      <MemberSignature Language="F#" Value="member this.Value : string" Usage="System.Fabric.Description.ConfigurationProperty.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="bc48a-114">Ruft den Wert der Einstellung ab.</span><span class="sxs-lookup"><span data-stu-id="bc48a-114">Gets the value of the setting.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="bc48a-115">Der Wert der Einstellung.</span><span class="sxs-lookup"><span data-stu-id="bc48a-115">The value of the setting.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>