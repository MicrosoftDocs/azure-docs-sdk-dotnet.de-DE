<Type Name="IWithExtension" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithExtension">
  <TypeSignature Language="C#" Value="public interface IWithExtension" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithExtension" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithExtension" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithExtension" />
  <TypeSignature Language="F#" Value="type IWithExtension = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Stufe der ein Update der virtuellen Maschine angeben können.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineNewExtension">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate&gt; DefineNewExtension (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate&gt; DefineNewExtension(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithExtension.DefineNewExtension(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineNewExtension (name As String) As IBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineNewExtension : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate&gt;" Usage="iWithExtension.DefineNewExtension name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Einen Verweisnamen für die Erweiterung.</param>
        <summary>
            Startet die Definition einer Erweiterung zum virtuellen Computer angefügt werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die erste Phase der Definition einer Erweiterung.</return>
      </Docs>
    </Member>
    <Member MemberName="UpdateExtension">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IUpdate UpdateExtension (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IUpdate UpdateExtension(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithExtension.UpdateExtension(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateExtension (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdateExtension : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IUpdate" Usage="iWithExtension.UpdateExtension name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Verweisname, der eine vorhandene Erweiterung.</param>
        <summary>
            Startet die Beschreibung des ein Update einer vorhandenen Erweiterung dieses virtuellen Computers an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die erste Phase eines Updates der Erweiterung.</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutExtension">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithoutExtension (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithoutExtension(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithExtension.WithoutExtension(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutExtension (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutExtension : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate" Usage="iWithExtension.WithoutExtension name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Verweisname der Erweiterung entfernt/deinstalliert werden.</param>
        <summary>
            Trennt eine Erweiterung des virtuellen Computers an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
  </Members>
</Type>