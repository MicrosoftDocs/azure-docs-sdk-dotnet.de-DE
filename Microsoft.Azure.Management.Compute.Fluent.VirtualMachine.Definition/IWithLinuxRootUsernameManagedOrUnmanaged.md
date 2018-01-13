<Type Name="IWithLinuxRootUsernameManagedOrUnmanaged" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxRootUsernameManagedOrUnmanaged">
  <TypeSignature Language="C#" Value="public interface IWithLinuxRootUsernameManagedOrUnmanaged" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithLinuxRootUsernameManagedOrUnmanaged" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxRootUsernameManagedOrUnmanaged" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithLinuxRootUsernameManagedOrUnmanaged" />
  <TypeSignature Language="F#" Value="type IWithLinuxRootUsernameManagedOrUnmanaged = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase der Definition eines Linux-virtuelle Computer festlegen, dass einen SSH-Root-Benutzernamen angeben.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithRootUsername">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxRootPasswordOrPublicKeyManagedOrUnmanaged WithRootUsername (string rootUserName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxRootPasswordOrPublicKeyManagedOrUnmanaged WithRootUsername(string rootUserName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxRootUsernameManagedOrUnmanaged.WithRootUsername(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRootUsername (rootUserName As String) As IWithLinuxRootPasswordOrPublicKeyManagedOrUnmanaged" />
      <MemberSignature Language="F#" Value="abstract member WithRootUsername : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxRootPasswordOrPublicKeyManagedOrUnmanaged" Usage="iWithLinuxRootUsernameManagedOrUnmanaged.WithRootUsername rootUserName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxRootPasswordOrPublicKeyManagedOrUnmanaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="rootUserName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="rootUserName">Ein Benutzername, befolgen die erforderlichen Namenskonvention für Linux-Benutzernamen.</param>
        <summary>
            Gibt ein SSH-Root-Benutzername für den virtuellen Linux-Computer an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>