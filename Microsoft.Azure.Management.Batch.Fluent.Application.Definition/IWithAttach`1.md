<Type Name="IWithAttach&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Batch.Fluent.Application.Definition.IWithAttach&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithAttach&lt;ParentT&gt; : Microsoft.Azure.Management.Batch.Fluent.Application.Definition.IWithApplicationPackage&lt;ParentT&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Definition.IInDefinition&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAttach`1&lt;ParentT&gt; implements class Microsoft.Azure.Management.Batch.Fluent.Application.Definition.IWithApplicationPackage`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Definition.IInDefinition`1&lt;!ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Fluent.Application.Definition.IWithAttach`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAttach(Of ParentT)&#xA;Implements IInDefinition(Of ParentT), IWithApplicationPackage(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithAttach&lt;'ParentT&gt; = interface&#xA;    interface IInDefinition&lt;'ParentT&gt;&#xA;    interface IWithApplicationPackage&lt;'ParentT&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Batch.Fluent.Application.Definition.IWithApplicationPackage&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Definition.IInDefinition&lt;ParentT&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="0335a-101">Die Phase des übergeordneten Elements Batch-Konto Definition wieder nach dem Anfügen dieser Definition.</span><span class="sxs-lookup"><span data-stu-id="0335a-101">The stage of the parent Batch account definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="0335a-102">Der abschließenden Phase der Anwendungsdefinition.</span><span class="sxs-lookup"><span data-stu-id="0335a-102">The final stage of the application definition.</span></span>
            <span data-ttu-id="0335a-103">Zu diesem Zeitpunkt alle verbleibenden Einstellungen an optionalen können angegeben werden, oder die Anwendungsdefinition an der Definition des übergeordneten Batch-Konto angefügt werden kann.</span><span class="sxs-lookup"><span data-stu-id="0335a-103">At this stage, any remaining optional settings can be specified, or the application definition can be attached to the parent batch account definition.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithAllowUpdates">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Fluent.Application.Definition.IWithAttach&lt;ParentT&gt; WithAllowUpdates (bool allowUpdates);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Batch.Fluent.Application.Definition.IWithAttach`1&lt;!ParentT&gt; WithAllowUpdates(bool allowUpdates) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.Application.Definition.IWithAttach`1.WithAllowUpdates(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithAllowUpdates (allowUpdates As Boolean) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithAllowUpdates : bool -&gt; Microsoft.Azure.Management.Batch.Fluent.Application.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithAttach.WithAllowUpdates allowUpdates" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Fluent.Application.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="allowUpdates" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="allowUpdates"><span data-ttu-id="0335a-104">"True", um die automatische Updates der Anwendung, andernfalls "false" zuzulassen.</span><span class="sxs-lookup"><span data-stu-id="0335a-104">True to allow the automatic updates of application, otherwise false.</span></span></param>
        <summary>
            <span data-ttu-id="0335a-105">Die Phase der Definition eines Batch-Anwendung ermöglicht die automatische Anwendung von Updates.</span><span class="sxs-lookup"><span data-stu-id="0335a-105">The stage of a Batch application definition allowing automatic application updates.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="0335a-106">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="0335a-106">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithDisplayName">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Fluent.Application.Definition.IWithAttach&lt;ParentT&gt; WithDisplayName (string displayName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Batch.Fluent.Application.Definition.IWithAttach`1&lt;!ParentT&gt; WithDisplayName(string displayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.Application.Definition.IWithAttach`1.WithDisplayName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDisplayName (displayName As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithDisplayName : string -&gt; Microsoft.Azure.Management.Batch.Fluent.Application.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithAttach.WithDisplayName displayName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Fluent.Application.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="displayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="displayName"><span data-ttu-id="0335a-107">Ein Anzeigename.</span><span class="sxs-lookup"><span data-stu-id="0335a-107">A display name.</span></span></param>
        <summary>
            <span data-ttu-id="0335a-108">Gibt einen Anzeigenamen für die Batch-Anwendung an.</span><span class="sxs-lookup"><span data-stu-id="0335a-108">Specifies a display name for the Batch application.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="0335a-109">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="0335a-109">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>