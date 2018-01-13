<Type Name="IWithLinuxRootPasswordOrPublicKeyUnmanaged" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxRootPasswordOrPublicKeyUnmanaged">
  <TypeSignature Language="C#" Value="public interface IWithLinuxRootPasswordOrPublicKeyUnmanaged" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithLinuxRootPasswordOrPublicKeyUnmanaged" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxRootPasswordOrPublicKeyUnmanaged" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithLinuxRootPasswordOrPublicKeyUnmanaged" />
  <TypeSignature Language="F#" Value="type IWithLinuxRootPasswordOrPublicKeyUnmanaged = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase der Definition eines Linux-virtuelle Computer festlegen, dass ein SSH-Root-Kennwort oder einen öffentlichen Schlüssel an.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithRootPassword">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxCreateUnmanaged WithRootPassword (string rootPassword);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxCreateUnmanaged WithRootPassword(string rootPassword) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxRootPasswordOrPublicKeyUnmanaged.WithRootPassword(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRootPassword (rootPassword As String) As IWithLinuxCreateUnmanaged" />
      <MemberSignature Language="F#" Value="abstract member WithRootPassword : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxCreateUnmanaged" Usage="iWithLinuxRootPasswordOrPublicKeyUnmanaged.WithRootPassword rootPassword" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxCreateUnmanaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="rootPassword" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="rootPassword">Ein Kennwort, befolgen die Komplexität Kriterien für Azure Linux-VM-Kennwörter.</param>
        <summary>
            Gibt ein SSH-Root-Kennwort für den virtuellen Linux-Computer an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithSsh">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxCreateUnmanaged WithSsh (string publicKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxCreateUnmanaged WithSsh(string publicKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxRootPasswordOrPublicKeyUnmanaged.WithSsh(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSsh (publicKey As String) As IWithLinuxCreateUnmanaged" />
      <MemberSignature Language="F#" Value="abstract member WithSsh : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxCreateUnmanaged" Usage="iWithLinuxRootPasswordOrPublicKeyUnmanaged.WithSsh publicKey" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxCreateUnmanaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="publicKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="publicKey">eine öffentliche SSH-Schlüssel in das PEM-Format.</param>
        <summary>
            Gibt einen öffentlichen SSH-Schlüssel an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>