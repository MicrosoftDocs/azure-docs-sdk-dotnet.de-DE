<Type Name="ISupportsBatchCreation&lt;IFluentResourceT&gt;" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsBatchCreation&lt;IFluentResourceT&gt;">
  <TypeSignature Language="C#" Value="public interface ISupportsBatchCreation&lt;IFluentResourceT&gt; where IFluentResourceT : IHasId" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ISupportsBatchCreation`1&lt;(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId) IFluentResourceT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsBatchCreation`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface ISupportsBatchCreation(Of IFluentResourceT)" />
  <TypeSignature Language="F#" Value="type ISupportsBatchCreation&lt;'IFluentResourceT (requires 'IFluentResourceT :&gt; IHasId)&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="IFluentResourceT">
      <Constraints>
        <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId</InterfaceName>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="IFluentResourceT"><span data-ttu-id="443ce-101">die oberste Ebene Azure Ressourcentyp</span><span class="sxs-lookup"><span data-stu-id="443ce-101">the top level Azure resource type</span></span></typeparam>
    <summary>
            <span data-ttu-id="443ce-102">Bereitstellen von Zugriff auf ein Batch von Azure-Top Level Ressourcen vom gleichen Typ erstellt.</span><span class="sxs-lookup"><span data-stu-id="443ce-102">Providing access to creating a batch of Azure top level resources of same type.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Core.ICreatedResources&lt;IFluentResourceT&gt; Create (params Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;IFluentResourceT&gt;[] creatables);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ICreatedResources`1&lt;!IFluentResourceT&gt; Create(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;!IFluentResourceT&gt;[] creatables) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsBatchCreation`1.Create(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{`0}[])" />
      <MemberSignature Language="VB.NET" Value="Public Function Create (ParamArray creatables As ICreatable(Of IFluentResourceT)()) As ICreatedResources(Of IFluentResourceT)" />
      <MemberSignature Language="F#" Value="abstract member Create : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;'IFluentResourceT (requires 'IFluentResourceT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId)&gt;[] -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.ICreatedResources&lt;'IFluentResourceT (requires 'IFluentResourceT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId)&gt;" Usage="iSupportsBatchCreation.Create creatables" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ICreatedResources&lt;IFluentResourceT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="creatables" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;IFluentResourceT&gt;[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="creatables"><span data-ttu-id="443ce-103">die Creatables im batch</span><span class="sxs-lookup"><span data-stu-id="443ce-103">the creatables in the batch</span></span></param>
        <summary>
            <span data-ttu-id="443ce-104">Erstellt einen Satz (Batch) von Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="443ce-104">Creates a set (batch) of resources.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Core.ICreatedResources&lt;IFluentResourceT&gt; Create (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;IFluentResourceT&gt;&gt; creatables);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ICreatedResources`1&lt;!IFluentResourceT&gt; Create(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;!IFluentResourceT&gt;&gt; creatables) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsBatchCreation`1.Create(System.Collections.Generic.IEnumerable{Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{`0}})" />
      <MemberSignature Language="VB.NET" Value="Public Function Create (creatables As IEnumerable(Of ICreatable(Of IFluentResourceT))) As ICreatedResources(Of IFluentResourceT)" />
      <MemberSignature Language="F#" Value="abstract member Create : seq&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;'IFluentResourceT&gt;&gt; -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.ICreatedResources&lt;'IFluentResourceT (requires 'IFluentResourceT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId)&gt;" Usage="iSupportsBatchCreation.Create creatables" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ICreatedResources&lt;IFluentResourceT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="creatables" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;IFluentResourceT&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="creatables"><span data-ttu-id="443ce-105">die Creatables im batch</span><span class="sxs-lookup"><span data-stu-id="443ce-105">the creatables in the batch</span></span></param>
        <summary>
            <span data-ttu-id="443ce-106">Erstellt einen Satz (Batch) von Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="443ce-106">Creates a set (batch) of resources.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Core.ICreatedResources&lt;IFluentResourceT&gt;&gt; CreateAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;IFluentResourceT&gt;&gt; creatables, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ICreatedResources`1&lt;!IFluentResourceT&gt;&gt; CreateAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;!IFluentResourceT&gt;&gt; creatables, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsBatchCreation`1.CreateAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{`0}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : seq&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;'IFluentResourceT&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Core.ICreatedResources&lt;'IFluentResourceT&gt;&gt;" Usage="iSupportsBatchCreation.CreateAsync (creatables, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Core.ICreatedResources&lt;IFluentResourceT&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="creatables" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;IFluentResourceT&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="creatables"><span data-ttu-id="443ce-107">die Creatables im batch</span><span class="sxs-lookup"><span data-stu-id="443ce-107">the creatables in the batch</span></span></param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="443ce-108">Erstellt einen Satz (Batch) von Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="443ce-108">Creates a set (batch) of resources.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>