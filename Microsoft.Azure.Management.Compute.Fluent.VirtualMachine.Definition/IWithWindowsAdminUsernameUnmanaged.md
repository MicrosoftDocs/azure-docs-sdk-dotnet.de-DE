<Type Name="IWithWindowsAdminUsernameUnmanaged" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsAdminUsernameUnmanaged">
  <TypeSignature Language="C#" Value="public interface IWithWindowsAdminUsernameUnmanaged" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithWindowsAdminUsernameUnmanaged" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsAdminUsernameUnmanaged" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithWindowsAdminUsernameUnmanaged" />
  <TypeSignature Language="F#" Value="type IWithWindowsAdminUsernameUnmanaged = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase der Definition des Windows-VM ermöglicht Administratorbenutzernamen an.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithAdminUsername">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsAdminPasswordUnmanaged WithAdminUsername (string adminUserName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsAdminPasswordUnmanaged WithAdminUsername(string adminUserName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsAdminUsernameUnmanaged.WithAdminUsername(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithAdminUsername (adminUserName As String) As IWithWindowsAdminPasswordUnmanaged" />
      <MemberSignature Language="F#" Value="abstract member WithAdminUsername : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsAdminPasswordUnmanaged" Usage="iWithWindowsAdminUsernameUnmanaged.WithAdminUsername adminUserName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsAdminPasswordUnmanaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="adminUserName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="adminUserName">ein Benutzername, befolgen die erforderlichen Namenskonvention für Windows-Benutzernamen.</param>
        <summary>
            Gibt an, der Benutzername des Administrators für den virtuellen Windows-Computer.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>