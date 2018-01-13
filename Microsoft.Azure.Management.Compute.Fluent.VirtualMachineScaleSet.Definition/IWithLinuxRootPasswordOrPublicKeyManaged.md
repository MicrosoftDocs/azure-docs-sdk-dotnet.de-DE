<Type Name="IWithLinuxRootPasswordOrPublicKeyManaged" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootPasswordOrPublicKeyManaged">
  <TypeSignature Language="C#" Value="public interface IWithLinuxRootPasswordOrPublicKeyManaged" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithLinuxRootPasswordOrPublicKeyManaged" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootPasswordOrPublicKeyManaged" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithLinuxRootPasswordOrPublicKeyManaged" />
  <TypeSignature Language="F#" Value="type IWithLinuxRootPasswordOrPublicKeyManaged = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase der Linux-VM-Skalierungsgruppe festgelegt Definition ermöglichen, öffentliche Schlüssel oder SSH-Root-Kennwort angegeben.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithRootPassword">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxCreateManaged WithRootPassword (string rootPassword);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxCreateManaged WithRootPassword(string rootPassword) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootPasswordOrPublicKeyManaged.WithRootPassword(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRootPassword (rootPassword As String) As IWithLinuxCreateManaged" />
      <MemberSignature Language="F#" Value="abstract member WithRootPassword : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxCreateManaged" Usage="iWithLinuxRootPasswordOrPublicKeyManaged.WithRootPassword rootPassword" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxCreateManaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="rootPassword" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="rootPassword">Ein Kennwort, befolgen die Komplexität Kriterien für Azure Linux-VM-Kennwörter.</param>
        <summary>
            Gibt das SSH-Root-Kennwort für den virtuellen Linux-Computer.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithSsh">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxCreateManaged WithSsh (string publicKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxCreateManaged WithSsh(string publicKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootPasswordOrPublicKeyManaged.WithSsh(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSsh (publicKey As String) As IWithLinuxCreateManaged" />
      <MemberSignature Language="F#" Value="abstract member WithSsh : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxCreateManaged" Usage="iWithLinuxRootPasswordOrPublicKeyManaged.WithSsh publicKey" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxCreateManaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="publicKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="publicKey">der öffentliche SSH-Schlüssel im PEM-Format.</param>
        <summary>
            Gibt den öffentlichen SSH-Schlüssel an.
            Jeder Aufruf dieser Methode hinzugefügt die Liste der öffentliche Schlüssel des virtuellen Computers den angegebenen öffentlichen Schlüssel.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>