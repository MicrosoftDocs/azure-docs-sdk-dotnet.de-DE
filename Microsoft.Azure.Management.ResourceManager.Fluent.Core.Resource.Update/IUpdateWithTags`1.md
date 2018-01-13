<Type Name="IUpdateWithTags&lt;T&gt;" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Update.IUpdateWithTags&lt;T&gt;">
  <TypeSignature Language="C#" Value="public interface IUpdateWithTags&lt;T&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IUpdateWithTags`1&lt;T&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Update.IUpdateWithTags`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IUpdateWithTags(Of T)" />
  <TypeSignature Language="F#" Value="type IUpdateWithTags&lt;'T&gt; = interface" />
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
    <Member MemberName="WithoutTag">
      <MemberSignature Language="C#" Value="public T WithoutTag (string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !T WithoutTag(string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Update.IUpdateWithTags`1.WithoutTag(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutTag (key As String) As T" />
      <MemberSignature Language="F#" Value="abstract member WithoutTag : string -&gt; 'T" Usage="iUpdateWithTags.WithoutTag key" />
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
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="1dcbe-101">Das Ändern des Tags entfernen</span><span class="sxs-lookup"><span data-stu-id="1dcbe-101">key the key of the tag to remove</span></span></param>
        <summary>
            <span data-ttu-id="1dcbe-102">Entfernt ein Tag aus der Ressource an.</span><span class="sxs-lookup"><span data-stu-id="1dcbe-102">Removes a tag from the resource.</span></span>
            </summary>
        <returns><span data-ttu-id="1dcbe-103">die nächste Phase des Ressource-Updates</span><span class="sxs-lookup"><span data-stu-id="1dcbe-103">the next stage of the resource update</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithTag">
      <MemberSignature Language="C#" Value="public T WithTag (string key, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !T WithTag(string key, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Update.IUpdateWithTags`1.WithTag(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithTag (key As String, value As String) As T" />
      <MemberSignature Language="F#" Value="abstract member WithTag : string * string -&gt; 'T" Usage="iUpdateWithTags.WithTag (key, value)" />
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
        <param name="key"><span data-ttu-id="1dcbe-104">Schlüssel des Schlüssels für das tag</span><span class="sxs-lookup"><span data-stu-id="1dcbe-104">key the key for the tag</span></span></param>
        <param name="value"><span data-ttu-id="1dcbe-105">der Wert für das tag</span><span class="sxs-lookup"><span data-stu-id="1dcbe-105">value the value for the tag</span></span></param>
        <summary>
            <span data-ttu-id="1dcbe-106">Fügt ein Tag auf die Ressource an.</span><span class="sxs-lookup"><span data-stu-id="1dcbe-106">Adds a tag to the resource.</span></span>
            </summary>
        <returns><span data-ttu-id="1dcbe-107">die nächste Phase des Ressource-Updates</span><span class="sxs-lookup"><span data-stu-id="1dcbe-107">the next stage of the resource update</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithTags">
      <MemberSignature Language="C#" Value="public T WithTags (System.Collections.Generic.IDictionary&lt;string,string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !T WithTags(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Update.IUpdateWithTags`1.WithTags(System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithTags (tags As IDictionary(Of String, String)) As T" />
      <MemberSignature Language="F#" Value="abstract member WithTags : System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; 'T" Usage="iUpdateWithTags.WithTags tags" />
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
        <param name="tags"><span data-ttu-id="1dcbe-108">RFID-Transponder eine {@link Zuordnung} von Tags</span><span class="sxs-lookup"><span data-stu-id="1dcbe-108">tags a {@link Map} of tags</span></span></param>
        <summary>
            <span data-ttu-id="1dcbe-109">Gibt an, Tags für die Ressource als eine {@link Zuordnung}.</span><span class="sxs-lookup"><span data-stu-id="1dcbe-109">Specifies tags for the resource as a {@link Map}.</span></span>
            </summary>
        <returns><span data-ttu-id="1dcbe-110">die nächste Phase des Ressource-Updates</span><span class="sxs-lookup"><span data-stu-id="1dcbe-110">the next stage of the resource update</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>