<Type Name="ComposeDeploymentDescription" FullName="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription">
  <TypeSignature Language="C#" Value="public sealed class ComposeDeploymentDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ComposeDeploymentDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ComposeDeploymentDescription" />
  <TypeSignature Language="F#" Value="type ComposeDeploymentDescription = class" />
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
      <para><span data-ttu-id="9ff50-101">Beschreibt eine Compose-Bereitstellung mit System.Fabric.FabricClient.ComposeDeploymentClient.CreateComposeDeploymentAsync(Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription) erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="9ff50-101">Describes a compose deployment to be created by using System.Fabric.FabricClient.ComposeDeploymentClient.CreateComposeDeploymentAsync(Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription) .</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ComposeDeploymentDescription (string deploymentName, string composeFilePath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string deploymentName, string composeFilePath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (deploymentName As String, composeFilePath As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription : string * string -&gt; Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription" Usage="new Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription (deploymentName, composeFilePath)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="composeFilePath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deploymentName">
          <para><span data-ttu-id="9ff50-102">Name der Bereitstellung zu verfassen.</span><span class="sxs-lookup"><span data-stu-id="9ff50-102">Name of compose deployment.</span></span></para>
        </param>
        <param name="composeFilePath">
          <para><span data-ttu-id="9ff50-103">Der Pfad zur Datei verfassen.</span><span class="sxs-lookup"><span data-stu-id="9ff50-103">Path to the compose file.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="9ff50-104">Instanziiert eine Instanz des <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription" /> mit den Instanznamen für die Anwendung und den Pfad zu den Dateien verfassen.</span><span class="sxs-lookup"><span data-stu-id="9ff50-104">Instantiates an instance of <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription" /> with the application instance name, and the path to the compose files.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComposeFilePath">
      <MemberSignature Language="C#" Value="public string ComposeFilePath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ComposeFilePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription.ComposeFilePath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ComposeFilePath As String" />
      <MemberSignature Language="F#" Value="member this.ComposeFilePath : string" Usage="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription.ComposeFilePath" />
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
          <para><span data-ttu-id="9ff50-105">Ruft den Pfad zur Datei verfassen.</span><span class="sxs-lookup"><span data-stu-id="9ff50-105">Gets the path to the compose file.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="9ff50-106">Der Pfad der verfassen.</span><span class="sxs-lookup"><span data-stu-id="9ff50-106">The compose file path.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerRegistryPassword">
      <MemberSignature Language="C#" Value="public string ContainerRegistryPassword { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContainerRegistryPassword" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription.ContainerRegistryPassword" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerRegistryPassword As String" />
      <MemberSignature Language="F#" Value="member this.ContainerRegistryPassword : string with get, set" Usage="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription.ContainerRegistryPassword" />
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
          <para><span data-ttu-id="9ff50-107">Ruft den Container Registrierung Kennwort ab.</span><span class="sxs-lookup"><span data-stu-id="9ff50-107">Gets the container registry password.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="9ff50-108">Das Benutzerkennwort für den Container Registrierung.</span><span class="sxs-lookup"><span data-stu-id="9ff50-108">The container registry user password.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerRegistryUserName">
      <MemberSignature Language="C#" Value="public string ContainerRegistryUserName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContainerRegistryUserName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription.ContainerRegistryUserName" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerRegistryUserName As String" />
      <MemberSignature Language="F#" Value="member this.ContainerRegistryUserName : string with get, set" Usage="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription.ContainerRegistryUserName" />
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
          <para><span data-ttu-id="9ff50-109">Ruft den Container Registrierung-Benutzernamen ab.</span><span class="sxs-lookup"><span data-stu-id="9ff50-109">Gets the container registry user name.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="9ff50-110">Der Benutzername für den Container Registrierung.</span><span class="sxs-lookup"><span data-stu-id="9ff50-110">The container registry user name.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeploymentName">
      <MemberSignature Language="C#" Value="public string DeploymentName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DeploymentName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription.DeploymentName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeploymentName As String" />
      <MemberSignature Language="F#" Value="member this.DeploymentName : string" Usage="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription.DeploymentName" />
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
          <para><span data-ttu-id="9ff50-111">Ruft den Namen der Bereitstellung verfassen.</span><span class="sxs-lookup"><span data-stu-id="9ff50-111">Gets the name of the compose deployment.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="9ff50-112">Der Name der Bereitstellung verfassen.</span><span class="sxs-lookup"><span data-stu-id="9ff50-112">The name of the compose deployment.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsRegistryPasswordEncrypted">
      <MemberSignature Language="C#" Value="public bool IsRegistryPasswordEncrypted { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsRegistryPasswordEncrypted" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription.IsRegistryPasswordEncrypted" />
      <MemberSignature Language="VB.NET" Value="Public Property IsRegistryPasswordEncrypted As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsRegistryPasswordEncrypted : bool with get, set" Usage="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription.IsRegistryPasswordEncrypted" />
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
          <para><span data-ttu-id="9ff50-113">Ruft ab, wenn die Registrierung das angegebene Kennwort verschlüsselt ist.</span><span class="sxs-lookup"><span data-stu-id="9ff50-113">Gets if the registry password specified is encrypted or not.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="9ff50-114">"True", wenn die Registrierung Kennwort verschlüsselt ist.</span><span class="sxs-lookup"><span data-stu-id="9ff50-114">True if the registry password is encrypted.</span></span> <span data-ttu-id="9ff50-115">"False" andernfalls.</span><span class="sxs-lookup"><span data-stu-id="9ff50-115">False otherwise.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>