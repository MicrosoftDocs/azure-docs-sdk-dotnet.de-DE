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
      <para>Gibt eine Konfigurationseinstellung und ihren Wert, der verwendet werden kann, um einen Dienst oder Anwendung konfigurieren.</para>
      <para>Die Einstellungen werden in der Datei "Settings.xml" in das Manifest angegeben. Weitere Informationen finden Sie unter https://docs.microsoft.com/azure/service-fabric/service-fabric-application-model</para>
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
          <para>Entschlüsselt einen verschlüsselten Wert und wird als SecureString zurückgegeben.</para>
        </summary>
        <returns>
          <para>Gibt <see cref="T:System.Security.SecureString" />zurück.</para>
        </returns>
        <remarks>Finden Sie unter https://docs.microsoft.com/azure/service-fabric/service-fabric-application-secret-management ein Beispiel, wie Sie einen geheimen Schlüssel zu verschlüsseln und in der Konfiguration zu speichern und wie Sie mithilfe dieser Methode um den Wert zur Laufzeit zu entschlüsseln.</remarks>
        <exception cref="T:System.InvalidOperationException">
          <para>Der Wert, der die <see cref="T:System.Fabric.Description.ConfigurationProperty" /> werden nicht verschlüsselt.</para>
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
          <para>Ruft ein Flag, das angibt, ob die Konfiguration verschlüsselt ist. </para>
        </summary>
        <value>
          <para>Gibt "true" zurück, wenn die Konfiguration verschlüsselt wird; "false", andernfalls.</para>
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
          <para>Ruft ein Flag, das angibt, ob die Einstellung im Anwendungsmanifest außer Kraft gesetzt werden muss.</para>
        </summary>
        <value>
          <para>Flag, das angibt, ob die Einstellung im Anwendungsmanifest außer Kraft gesetzt werden muss.</para>
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
          <para>Ruft den Namen der Einstellung entsprechend den Angaben in der Datei "Settings.xml" in das Manifest ab.</para>
        </summary>
        <value>
          <para>Der Name der Einstellung.</para>
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
          <para>Ruft den Wert der Einstellung ab.</para>
        </summary>
        <value>
          <para>Der Wert der Einstellung.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>