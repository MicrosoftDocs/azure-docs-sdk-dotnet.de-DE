<Type Name="IWithRepositoryType&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.Definition.IWithRepositoryType&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithRepositoryType&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithRepositoryType`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.Definition.IWithRepositoryType`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithRepositoryType(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithRepositoryType&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="9a56f-101">die Phase der Definition des übergeordneten wieder nach dem Anfügen dieser Definition.</span><span class="sxs-lookup"><span data-stu-id="9a56f-101">The stage of the parent definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="9a56f-102">Eine Web-app Quelle Steuerelementdefinition ermöglicht Repository-Typ angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="9a56f-102">A web app source control definition allowing repository type to be specified.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithContinuouslyIntegratedGitHubRepository">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.Definition.IWithGitHubBranch&lt;ParentT&gt; WithContinuouslyIntegratedGitHubRepository (string url);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.Definition.IWithGitHubBranch`1&lt;!ParentT&gt; WithContinuouslyIntegratedGitHubRepository(string url) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.Definition.IWithRepositoryType`1.WithContinuouslyIntegratedGitHubRepository(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithContinuouslyIntegratedGitHubRepository (url As String) As IWithGitHubBranch(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithContinuouslyIntegratedGitHubRepository : string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.Definition.IWithGitHubBranch&lt;'ParentT&gt;" Usage="iWithRepositoryType.WithContinuouslyIntegratedGitHubRepository url" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.Definition.IWithGitHubBranch&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="url" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="url"><span data-ttu-id="9a56f-103">Die URL, die auf das Repository, z. B. https://github.com/Azure/azure-sdk-for-java verweist.</span><span class="sxs-lookup"><span data-stu-id="9a56f-103">The URL pointing to the repository, e.g. https://github.com/Azure/azure-sdk-for-java.</span></span></param>
        <summary>
            <span data-ttu-id="9a56f-104">Gibt das Repository, sodass ein GitHub-Repository zu werden.</span><span class="sxs-lookup"><span data-stu-id="9a56f-104">Specifies the repository to be a GitHub repository.</span></span> <span data-ttu-id="9a56f-105">Fortlaufende Integration wird eingeschaltet sein.</span><span class="sxs-lookup"><span data-stu-id="9a56f-105">Continuous integration will be turned on.</span></span>
            <span data-ttu-id="9a56f-106">Dieses Repository kann entweder öffentlich oder privat sein muss, Ihre GitHub-Zugriffstoken jedoch über ausreichende Berechtigungen für einen Webhook dem Repository hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="9a56f-106">This repository can be either public or private, but your GitHub access token must have enough privileges to add a webhook to the repository.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="9a56f-107">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="9a56f-107">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithContinuouslyIntegratedGitHubRepository">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.Definition.IWithGitHubBranch&lt;ParentT&gt; WithContinuouslyIntegratedGitHubRepository (string organization, string repository);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.Definition.IWithGitHubBranch`1&lt;!ParentT&gt; WithContinuouslyIntegratedGitHubRepository(string organization, string repository) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.Definition.IWithRepositoryType`1.WithContinuouslyIntegratedGitHubRepository(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithContinuouslyIntegratedGitHubRepository (organization As String, repository As String) As IWithGitHubBranch(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithContinuouslyIntegratedGitHubRepository : string * string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.Definition.IWithGitHubBranch&lt;'ParentT&gt;" Usage="iWithRepositoryType.WithContinuouslyIntegratedGitHubRepository (organization, repository)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.Definition.IWithGitHubBranch&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="organization" Type="System.String" />
        <Parameter Name="repository" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="organization"><span data-ttu-id="9a56f-108">Der Benutzername oder der Name der Organisation, das GitHub-Repository, z. B. Azure gehört.</span><span class="sxs-lookup"><span data-stu-id="9a56f-108">The user name or organization name the GitHub repository belongs to, e.g. Azure.</span></span></param>
        <param name="repository"><span data-ttu-id="9a56f-109">Der Name des Repositorys, z. B. Azure-Sdk-für-Java.</span><span class="sxs-lookup"><span data-stu-id="9a56f-109">The name of the repository, e.g. azure-sdk-for-java.</span></span></param>
        <summary>
            <span data-ttu-id="9a56f-110">Gibt das Repository, sodass ein GitHub-Repository zu werden.</span><span class="sxs-lookup"><span data-stu-id="9a56f-110">Specifies the repository to be a GitHub repository.</span></span> <span data-ttu-id="9a56f-111">Fortlaufende Integration wird eingeschaltet sein.</span><span class="sxs-lookup"><span data-stu-id="9a56f-111">Continuous integration will be turned on.</span></span>
            <span data-ttu-id="9a56f-112">Dieses Repository kann entweder öffentlich oder privat sein muss, Ihre GitHub-Zugriffstoken jedoch über ausreichende Berechtigungen für einen Webhook dem Repository hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="9a56f-112">This repository can be either public or private, but your GitHub access token must have enough privileges to add a webhook to the repository.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="9a56f-113">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="9a56f-113">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithPublicGitRepository">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.Definition.IWithBranch&lt;ParentT&gt; WithPublicGitRepository (string url);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.Definition.IWithBranch`1&lt;!ParentT&gt; WithPublicGitRepository(string url) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.Definition.IWithRepositoryType`1.WithPublicGitRepository(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPublicGitRepository (url As String) As IWithBranch(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithPublicGitRepository : string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.Definition.IWithBranch&lt;'ParentT&gt;" Usage="iWithRepositoryType.WithPublicGitRepository url" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.Definition.IWithBranch&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="url" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="url"><span data-ttu-id="9a56f-114">Die Url des Git-Repositorys.</span><span class="sxs-lookup"><span data-stu-id="9a56f-114">The url of the Git repository.</span></span></param>
        <summary>
            <span data-ttu-id="9a56f-115">Gibt das Repository, um einen öffentlichen externen Repositorys, Git oder mercurial behandelt werden.</span><span class="sxs-lookup"><span data-stu-id="9a56f-115">Specifies the repository to be a public external repository, either Git or Mercurial.</span></span>
            <span data-ttu-id="9a56f-116">Fortlaufende Integration wird nicht aktiviert werden.</span><span class="sxs-lookup"><span data-stu-id="9a56f-116">Continuous integration will not be turned on.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="9a56f-117">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="9a56f-117">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithPublicMercurialRepository">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.Definition.IWithBranch&lt;ParentT&gt; WithPublicMercurialRepository (string url);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.Definition.IWithBranch`1&lt;!ParentT&gt; WithPublicMercurialRepository(string url) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.Definition.IWithRepositoryType`1.WithPublicMercurialRepository(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPublicMercurialRepository (url As String) As IWithBranch(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithPublicMercurialRepository : string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.Definition.IWithBranch&lt;'ParentT&gt;" Usage="iWithRepositoryType.WithPublicMercurialRepository url" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.Definition.IWithBranch&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="url" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="url"><span data-ttu-id="9a56f-118">Die Url des Mercurial-Repositorys.</span><span class="sxs-lookup"><span data-stu-id="9a56f-118">The url of the Mercurial repository.</span></span></param>
        <summary>
            <span data-ttu-id="9a56f-119">Gibt das Repository, um einen öffentlichen externen Repositorys, Git oder mercurial behandelt werden.</span><span class="sxs-lookup"><span data-stu-id="9a56f-119">Specifies the repository to be a public external repository, either Git or Mercurial.</span></span>
            <span data-ttu-id="9a56f-120">Fortlaufende Integration wird nicht aktiviert werden.</span><span class="sxs-lookup"><span data-stu-id="9a56f-120">Continuous integration will not be turned on.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="9a56f-121">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="9a56f-121">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>