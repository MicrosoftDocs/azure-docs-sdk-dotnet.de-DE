<Type Name="IDefinitionWithTags&lt;T&gt;" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;T&gt;">
  <TypeSignature Language="C#" Value="public interface IDefinitionWithTags&lt;T&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDefinitionWithTags`1&lt;T&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDefinitionWithTags(Of T)" />
  <TypeSignature Language="F#" Value="type IDefinitionWithTags&lt;'T&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="T">To be added.</typeparam>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithTag">
      <MemberSignature Language="C#" Value="public T WithTag (string key, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !T WithTag(string key, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags`1.WithTag(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithTag (key As String, value As String) As T" />
      <MemberSignature Language="F#" Value="abstract member WithTag : string * string -&gt; 'T" Usage="iDefinitionWithTags.WithTag (key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="47eb2-101">Schlüssel des Schlüssels für das tag</span><span class="sxs-lookup"><span data-stu-id="47eb2-101">key the key for the tag</span></span></param>
        <param name="value"><span data-ttu-id="47eb2-102">der Wert für das tag</span><span class="sxs-lookup"><span data-stu-id="47eb2-102">value the value for the tag</span></span></param>
        <summary>
            <span data-ttu-id="47eb2-103">Fügt ein Tag auf die Ressource an.</span><span class="sxs-lookup"><span data-stu-id="47eb2-103">Adds a tag to the resource.</span></span>
            </summary>
        <returns><span data-ttu-id="47eb2-104">die nächste Phase der Ressourcendefinition</span><span class="sxs-lookup"><span data-stu-id="47eb2-104">the next stage of the resource definition</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithTags">
      <MemberSignature Language="C#" Value="public T WithTags (System.Collections.Generic.IDictionary&lt;string,string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !T WithTags(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags`1.WithTags(System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithTags (tags As IDictionary(Of String, String)) As T" />
      <MemberSignature Language="F#" Value="abstract member WithTags : System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; 'T" Usage="iDefinitionWithTags.WithTags tags" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="tags"><span data-ttu-id="47eb2-105">RFID-Transponder eine {@link Zuordnung} von Tags</span><span class="sxs-lookup"><span data-stu-id="47eb2-105">tags a {@link Map} of tags</span></span></param>
        <summary>
            <span data-ttu-id="47eb2-106">Gibt an, Tags für die Ressource als eine {@link Zuordnung}.</span><span class="sxs-lookup"><span data-stu-id="47eb2-106">Specifies tags for the resource as a {@link Map}.</span></span>
            </summary>
        <returns><span data-ttu-id="47eb2-107">die nächste Phase der Ressourcendefinition</span><span class="sxs-lookup"><span data-stu-id="47eb2-107">the next stage of the resource definition</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>