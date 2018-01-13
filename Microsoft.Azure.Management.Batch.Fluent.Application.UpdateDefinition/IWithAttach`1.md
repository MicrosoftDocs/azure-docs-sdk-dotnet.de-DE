<Type Name="IWithAttach&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Batch.Fluent.Application.UpdateDefinition.IWithAttach&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithAttach&lt;ParentT&gt; : Microsoft.Azure.Management.Batch.Fluent.Application.UpdateDefinition.IWithApplicationPackage&lt;ParentT&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Update.IInUpdate&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAttach`1&lt;ParentT&gt; implements class Microsoft.Azure.Management.Batch.Fluent.Application.UpdateDefinition.IWithApplicationPackage`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Update.IInUpdate`1&lt;!ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Fluent.Application.UpdateDefinition.IWithAttach`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAttach(Of ParentT)&#xA;Implements IInUpdate(Of ParentT), IWithApplicationPackage(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithAttach&lt;'ParentT&gt; = interface&#xA;    interface IInUpdate&lt;'ParentT&gt;&#xA;    interface IWithApplicationPackage&lt;'ParentT&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Batch.Fluent.Application.UpdateDefinition.IWithApplicationPackage&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Update.IInUpdate&lt;ParentT&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="ParentT">Die Phase des übergeordneten Batch-Konto Updates wieder nach dem Anfügen dieser Definition.</typeparam>
    <summary>
            Die letzte Phase der Definition eines Batch-Anwendung.
            Zu diesem Zeitpunkt alle verbleibenden Einstellungen an optionalen können angegeben werden, oder die Anwendungsdefinition angefügt werden kann, an den übergeordneten Batch-Konto aktualisieren.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithAllowUpdates">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Fluent.Application.UpdateDefinition.IWithAttach&lt;ParentT&gt; WithAllowUpdates (bool allowUpdates);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Batch.Fluent.Application.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; WithAllowUpdates(bool allowUpdates) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.Application.UpdateDefinition.IWithAttach`1.WithAllowUpdates(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithAllowUpdates (allowUpdates As Boolean) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithAllowUpdates : bool -&gt; Microsoft.Azure.Management.Batch.Fluent.Application.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithAttach.WithAllowUpdates allowUpdates" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Fluent.Application.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="allowUpdates" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="allowUpdates">"True", um automatische Updates einer Batch-Anwendung, andernfalls "false" zuzulassen.</param>
        <summary>
            Kann automatische Anwendungsupdates an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithDisplayName">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Fluent.Application.UpdateDefinition.IWithAttach&lt;ParentT&gt; WithDisplayName (string displayName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Batch.Fluent.Application.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; WithDisplayName(string displayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.Application.UpdateDefinition.IWithAttach`1.WithDisplayName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDisplayName (displayName As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithDisplayName : string -&gt; Microsoft.Azure.Management.Batch.Fluent.Application.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithAttach.WithDisplayName displayName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Fluent.Application.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="displayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="displayName">ein Anzeigename für die Anwendung.</param>
        <summary>
            Gibt den Anzeigenamen für die Batch-Anwendung an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>