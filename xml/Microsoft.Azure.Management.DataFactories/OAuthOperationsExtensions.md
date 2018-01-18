<Type Name="OAuthOperationsExtensions" FullName="Microsoft.Azure.Management.DataFactories.OAuthOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class OAuthOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit OAuthOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.OAuthOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module OAuthOperationsExtensions" />
  <TypeSignature Language="F#" Value="type OAuthOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.AuthorizationSessionGetResponse Get (this Microsoft.Azure.Management.DataFactories.IOAuthOperations operations, string resourceGroupName, string dataFactoryName, string linkedServiceType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.AuthorizationSessionGetResponse Get(class Microsoft.Azure.Management.DataFactories.IOAuthOperations operations, string resourceGroupName, string dataFactoryName, string linkedServiceType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.OAuthOperationsExtensions.Get(Microsoft.Azure.Management.DataFactories.IOAuthOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IOAuthOperations, resourceGroupName As String, dataFactoryName As String, linkedServiceType As String) As AuthorizationSessionGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataFactories.IOAuthOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.AuthorizationSessionGetResponse" Usage="Microsoft.Azure.Management.DataFactories.OAuthOperationsExtensions.Get (operations, resourceGroupName, dataFactoryName, linkedServiceType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.AuthorizationSessionGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IOAuthOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="linkedServiceType" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="794aa-101">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IOAuthOperations.</span><span class="sxs-lookup"><span data-stu-id="794aa-101">Reference to the Microsoft.Azure.Management.DataFactories.Core.IOAuthOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="794aa-102">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="794aa-102">Required.</span></span> <span data-ttu-id="794aa-103">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="794aa-103">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="794aa-104">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="794aa-104">Required.</span></span> <span data-ttu-id="794aa-105">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="794aa-105">A unique data factory instance name.</span></span>
            </param>
        <param name="linkedServiceType">
            <span data-ttu-id="794aa-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="794aa-106">Required.</span></span> <span data-ttu-id="794aa-107">Der Typ des verknüpften OAuth-Dienst.</span><span class="sxs-lookup"><span data-stu-id="794aa-107">The type of OAuth linked service.</span></span>
            </param>
        <summary>
            <span data-ttu-id="794aa-108">Ruft eine Sitzung für OAuth Authorization ab.</span><span class="sxs-lookup"><span data-stu-id="794aa-108">Gets an OAuth authorization session.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="794aa-109">Get-Autorisierung Sitzung Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="794aa-109">The Get authorization session operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.AuthorizationSessionGetResponse&gt; GetAsync (this Microsoft.Azure.Management.DataFactories.IOAuthOperations operations, string resourceGroupName, string dataFactoryName, string linkedServiceType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.AuthorizationSessionGetResponse&gt; GetAsync(class Microsoft.Azure.Management.DataFactories.IOAuthOperations operations, string resourceGroupName, string dataFactoryName, string linkedServiceType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.OAuthOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataFactories.IOAuthOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IOAuthOperations, resourceGroupName As String, dataFactoryName As String, linkedServiceType As String) As Task(Of AuthorizationSessionGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataFactories.IOAuthOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.AuthorizationSessionGetResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.OAuthOperationsExtensions.GetAsync (operations, resourceGroupName, dataFactoryName, linkedServiceType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.AuthorizationSessionGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IOAuthOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="linkedServiceType" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="794aa-110">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IOAuthOperations.</span><span class="sxs-lookup"><span data-stu-id="794aa-110">Reference to the Microsoft.Azure.Management.DataFactories.Core.IOAuthOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="794aa-111">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="794aa-111">Required.</span></span> <span data-ttu-id="794aa-112">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="794aa-112">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="794aa-113">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="794aa-113">Required.</span></span> <span data-ttu-id="794aa-114">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="794aa-114">A unique data factory instance name.</span></span>
            </param>
        <param name="linkedServiceType">
            <span data-ttu-id="794aa-115">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="794aa-115">Required.</span></span> <span data-ttu-id="794aa-116">Der Typ des verknüpften OAuth-Dienst.</span><span class="sxs-lookup"><span data-stu-id="794aa-116">The type of OAuth linked service.</span></span>
            </param>
        <summary>
            <span data-ttu-id="794aa-117">Ruft eine Sitzung für OAuth Authorization ab.</span><span class="sxs-lookup"><span data-stu-id="794aa-117">Gets an OAuth authorization session.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="794aa-118">Get-Autorisierung Sitzung Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="794aa-118">The Get authorization session operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>