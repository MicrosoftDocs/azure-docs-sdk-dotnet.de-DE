<Type Name="IWithParentResource&lt;T,ParentT&gt;" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChild.Definition.IWithParentResource&lt;T,ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithParentResource&lt;T,ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithParentResource`2&lt;T, ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChild.Definition.IWithParentResource`2" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithParentResource(Of T, ParentT)" />
  <TypeSignature Language="F#" Value="type IWithParentResource&lt;'T, 'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="T">To be added.</typeparam>
    <typeparam name="ParentT">To be added.</typeparam>
    <summary>
            <span data-ttu-id="0d186-101">Einer Ressourcendefinition, sodass eine neue Ressourcengruppe erstellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="0d186-101">A resource definition allowing a new resource group to be created.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingParentResource">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;T&gt; WithExistingParentResource (ParentT existingParentResource);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;!T&gt; WithExistingParentResource(!ParentT existingParentResource) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChild.Definition.IWithParentResource`2.WithExistingParentResource(`1)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingParentResource (existingParentResource As ParentT) As ICreatable(Of T)" />
      <MemberSignature Language="F#" Value="abstract member WithExistingParentResource : 'ParentT -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;'T&gt;" Usage="iWithParentResource.WithExistingParentResource existingParentResource" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="existingParentResource" Type="ParentT" />
      </Parameters>
      <Docs>
        <param name="existingParentResource"><span data-ttu-id="0d186-102">die übergeordnete Ressource unter dem diese Ressource erstellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="0d186-102">The parent resource under which this resource to be created.</span></span></param>
        <summary>
            <span data-ttu-id="0d186-103">Erstellt eine neue untergeordnete Ressource unter der übergeordneten Ressource.</span><span class="sxs-lookup"><span data-stu-id="0d186-103">Creates a new child resource under parent resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="0d186-104">Für die untergeordnete Ressource erstellt.</span><span class="sxs-lookup"><span data-stu-id="0d186-104">The creatable for the child resource.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithExistingParentResource">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;T&gt; WithExistingParentResource (string groupName, string parentName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;!T&gt; WithExistingParentResource(string groupName, string parentName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChild.Definition.IWithParentResource`2.WithExistingParentResource(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingParentResource (groupName As String, parentName As String) As ICreatable(Of T)" />
      <MemberSignature Language="F#" Value="abstract member WithExistingParentResource : string * string -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;'T&gt;" Usage="iWithParentResource.WithExistingParentResource (groupName, parentName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="groupName" Type="System.String" />
        <Parameter Name="parentName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="groupName"><span data-ttu-id="0d186-105">der Name der Ressourcengruppe für die übergeordnete Ressource.</span><span class="sxs-lookup"><span data-stu-id="0d186-105">The name of the resource group for parent resource.</span></span></param>
        <param name="parentName"><span data-ttu-id="0d186-106">der Name der übergeordneten Ressource.</span><span class="sxs-lookup"><span data-stu-id="0d186-106">The name of the parent resource.</span></span></param>
        <summary>
            <span data-ttu-id="0d186-107">Erstellt eine neue untergeordnete Ressource unter der übergeordneten Ressource.</span><span class="sxs-lookup"><span data-stu-id="0d186-107">Creates a new child resource under parent resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="0d186-108">Für die untergeordnete Ressource erstellt.</span><span class="sxs-lookup"><span data-stu-id="0d186-108">The creatable for the child resource.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewParentResource">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;T&gt; WithNewParentResource (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;ParentT&gt; parentResourceCreatable);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;!T&gt; WithNewParentResource(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;!ParentT&gt; parentResourceCreatable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChild.Definition.IWithParentResource`2.WithNewParentResource(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{`1})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewParentResource (parentResourceCreatable As ICreatable(Of ParentT)) As ICreatable(Of T)" />
      <MemberSignature Language="F#" Value="abstract member WithNewParentResource : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;'ParentT&gt; -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;'T&gt;" Usage="iWithParentResource.WithNewParentResource parentResourceCreatable" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentResourceCreatable" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;ParentT&gt;" />
      </Parameters>
      <Docs>
        <param name="parentResourceCreatable"><span data-ttu-id="0d186-109">Eine erstellbare Definition für die übergeordnete Ressource.</span><span class="sxs-lookup"><span data-stu-id="0d186-109">A creatable definition for the parent resource.</span></span></param>
        <summary>
            <span data-ttu-id="0d186-110">Erstellt eine neue untergeordnete Ressource unter der übergeordneten Ressource.</span><span class="sxs-lookup"><span data-stu-id="0d186-110">Creates a new child resource under parent resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="0d186-111">Für die untergeordnete Ressource erstellt.</span><span class="sxs-lookup"><span data-stu-id="0d186-111">The creatable for the child resource.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>