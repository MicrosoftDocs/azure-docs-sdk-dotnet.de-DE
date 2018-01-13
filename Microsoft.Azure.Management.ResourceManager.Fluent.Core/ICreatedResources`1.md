<Type Name="ICreatedResources&lt;ResourceT&gt;" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ICreatedResources&lt;ResourceT&gt;">
  <TypeSignature Language="C#" Value="public interface ICreatedResources&lt;ResourceT&gt; : System.Collections.Generic.IEnumerable&lt;ResourceT&gt; where ResourceT : IHasId" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ICreatedResources`1&lt;(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId) ResourceT&gt; implements class System.Collections.Generic.IEnumerable`1&lt;!ResourceT&gt;, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ICreatedResources`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface ICreatedResources(Of ResourceT)&#xA;Implements IEnumerable(Of ResourceT)" />
  <TypeSignature Language="F#" Value="type ICreatedResources&lt;'ResourceT (requires 'ResourceT :&gt; IHasId)&gt; = interface&#xA;    interface seq&lt;'ResourceT (requires 'ResourceT :&gt; IHasId)&gt;&#xA;    interface IEnumerable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ResourceT">
      <Constraints>
        <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId</InterfaceName>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;ResourceT&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="ResourceT"><span data-ttu-id="5696e-101">Der Typ der Ressource in diesem batch</span><span class="sxs-lookup"><span data-stu-id="5696e-101">the type of the resource in this batch</span></span></typeparam>
    <summary>
            <span data-ttu-id="5696e-102">Stellt das Ergebnis der Batch erstellen Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="5696e-102">Represents result of batch of create operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreatedRelatedResource">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId CreatedRelatedResource (string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId CreatedRelatedResource(string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ICreatedResources`1.CreatedRelatedResource(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreatedRelatedResource (key As String) As IHasId" />
      <MemberSignature Language="F#" Value="abstract member CreatedRelatedResource : string -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId" Usage="iCreatedResources.CreatedRelatedResource key" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="5696e-103">der Schlüssel der Ressource</span><span class="sxs-lookup"><span data-stu-id="5696e-103">the key of the resource</span></span></param>
        <summary>
            <span data-ttu-id="5696e-104">Ruft einen erstellten Ressourcenpool mit dem angegebenen Schlüssel ab.</span><span class="sxs-lookup"><span data-stu-id="5696e-104">Gets a created resource with the given key.</span></span>
            </summary>
        <returns><span data-ttu-id="5696e-105">die erstellte Ressource</span><span class="sxs-lookup"><span data-stu-id="5696e-105">the created resource</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>