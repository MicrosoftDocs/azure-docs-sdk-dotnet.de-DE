<Type Name="IWithAutoUpgradeMinorVersion&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAutoUpgradeMinorVersion&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithAutoUpgradeMinorVersion&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAutoUpgradeMinorVersion`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAutoUpgradeMinorVersion`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAutoUpgradeMinorVersion(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithAutoUpgradeMinorVersion&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT">die Phase der Definition des übergeordneten wieder nach dem Anfügen dieser Definition.</typeparam>
    <summary>
            Die Phase von der virtuellen Maschine Erweiterung Definition ermöglicht aktivieren oder deaktivieren automatische Aktualisierung der Erweiterung beim beim Veröffentlichen eine neue Nebenversion des Image eines virtuellen Computers Erweiterung.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithMinorVersionAutoUpgrade">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAttach&lt;ParentT&gt; WithMinorVersionAutoUpgrade ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAttach`1&lt;!ParentT&gt; WithMinorVersionAutoUpgrade() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAutoUpgradeMinorVersion`1.WithMinorVersionAutoUpgrade" />
      <MemberSignature Language="VB.NET" Value="Public Function WithMinorVersionAutoUpgrade () As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithMinorVersionAutoUpgrade : unit -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithAutoUpgradeMinorVersion.WithMinorVersionAutoUpgrade " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            ermöglicht automatische Aktualisierung der Erweiterung.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutMinorVersionAutoUpgrade">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAttach&lt;ParentT&gt; WithoutMinorVersionAutoUpgrade ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAttach`1&lt;!ParentT&gt; WithoutMinorVersionAutoUpgrade() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAutoUpgradeMinorVersion`1.WithoutMinorVersionAutoUpgrade" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutMinorVersionAutoUpgrade () As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithoutMinorVersionAutoUpgrade : unit -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithAutoUpgradeMinorVersion.WithoutMinorVersionAutoUpgrade " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            deaktiviert die automatische Aktualisierung der Erweiterung.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>