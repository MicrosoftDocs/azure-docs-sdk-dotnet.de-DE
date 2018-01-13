<Type Name="ComposeDeploymentUpgradeDescription" FullName="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription">
  <TypeSignature Language="C#" Value="public sealed class ComposeDeploymentUpgradeDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ComposeDeploymentUpgradeDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ComposeDeploymentUpgradeDescription" />
  <TypeSignature Language="F#" Value="type ComposeDeploymentUpgradeDescription = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>Beschreibt eine Compose-Bereitstellung erstellt werden <see cref="M:System.Fabric.FabricClient.ComposeDeploymentClient.UpgradeComposeDeploymentAsync(System.Fabric.Description.ComposeDeploymentUpgradeDescriptionWrapper)" />.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ComposeDeploymentUpgradeDescription (string deploymentName, string[] composeFilePaths);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string deploymentName, string[] composeFilePaths) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription.#ctor(System.String,System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (deploymentName As String, composeFilePaths As String())" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription : string * string[] -&gt; Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription" Usage="new Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription (deploymentName, composeFilePaths)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="composeFilePaths" Type="System.String[]" />
      </Parameters>
      <Docs>
        <param name="deploymentName">To be added.</param>
        <param name="composeFilePaths">To be added.</param>
        <summary>
            Erstellt eine neue Instanz von <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription" />.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComposeFilePaths">
      <MemberSignature Language="C#" Value="public string[] ComposeFilePaths { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string[] ComposeFilePaths" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription.ComposeFilePaths" />
      <MemberSignature Language="VB.NET" Value="Public Property ComposeFilePaths As String()" />
      <MemberSignature Language="F#" Value="member this.ComposeFilePaths : string[] with get, set" Usage="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription.ComposeFilePaths" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft das Array von verfassen Dateipfade, die die nächste Version von dieser Bereitstellung beschreiben.</para>
        </summary>
        <value>
          <para>Array von Dateipfaden verfassen.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerRegistryPassword">
      <MemberSignature Language="C#" Value="public string ContainerRegistryPassword { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContainerRegistryPassword" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription.ContainerRegistryPassword" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerRegistryPassword As String" />
      <MemberSignature Language="F#" Value="member this.ContainerRegistryPassword : string with get, set" Usage="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription.ContainerRegistryPassword" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Benutzernamen im ContainerRegistryUserName-Parameter angegebene zugeordnete Kennwort ab.</para>
        </summary>
        <value>
          <para>Das Kennwort für den Container-Registrierung.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerRegistryUserName">
      <MemberSignature Language="C#" Value="public string ContainerRegistryUserName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContainerRegistryUserName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription.ContainerRegistryUserName" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerRegistryUserName As String" />
      <MemberSignature Language="F#" Value="member this.ContainerRegistryUserName : string with get, set" Usage="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription.ContainerRegistryUserName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Benutzernamen für die containerregistrierung, in dem die Bilder für die Container in dieser Bereitstellung vorhanden sind.</para>
        </summary>
        <value>
          <para>Der Benutzername für den Container Registrierung.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeploymentName">
      <MemberSignature Language="C#" Value="public string DeploymentName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DeploymentName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription.DeploymentName" />
      <MemberSignature Language="VB.NET" Value="Public Property DeploymentName As String" />
      <MemberSignature Language="F#" Value="member this.DeploymentName : string with get, set" Usage="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription.DeploymentName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Namen der Bereitstellung Verfassen der aktualisiert werden soll.</para>
        </summary>
        <value>
          <para>Der Name der Bereitstellung.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsRegistryPasswordEncrypted">
      <MemberSignature Language="C#" Value="public bool IsRegistryPasswordEncrypted { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsRegistryPasswordEncrypted" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription.IsRegistryPasswordEncrypted" />
      <MemberSignature Language="VB.NET" Value="Public Property IsRegistryPasswordEncrypted As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsRegistryPasswordEncrypted : bool with get, set" Usage="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription.IsRegistryPasswordEncrypted" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab, wenn im ContainerRegistryPassword-Parameter angegebene Kennwort verschlüsselt ist.</para>
        </summary>
        <value>
          <para>"True", wenn die Registrierung Kennwort verschlüsselt ist. "False" andernfalls.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradePolicyDescription">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.UpgradePolicyDescription UpgradePolicyDescription { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Description.UpgradePolicyDescription UpgradePolicyDescription" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription.UpgradePolicyDescription" />
      <MemberSignature Language="VB.NET" Value="Public Property UpgradePolicyDescription As UpgradePolicyDescription" />
      <MemberSignature Language="F#" Value="member this.UpgradePolicyDescription : System.Fabric.Description.UpgradePolicyDescription with get, set" Usage="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription.UpgradePolicyDescription" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.UpgradePolicyDescription</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt die Beschreibung der Richtlinie, die verwendet werden, für die Aktualisierung dieser Bereitstellung zu erstellen.</para>
        </summary>
        <value>
          <para>Die Beschreibung der Richtlinie, die verwendet werden, für die Aktualisierung dieses bilden Bereitstellung.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>