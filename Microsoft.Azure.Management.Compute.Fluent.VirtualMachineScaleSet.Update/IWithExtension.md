<Type Name="IWithExtension" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithExtension">
  <TypeSignature Language="C#" Value="public interface IWithExtension" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithExtension" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithExtension" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithExtension" />
  <TypeSignature Language="F#" Value="type IWithExtension = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase der virtuellen Maschine Definition ermöglicht Erweiterungen an.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineNewExtension">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply&gt; DefineNewExtension (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply&gt; DefineNewExtension(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithExtension.DefineNewExtension(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineNewExtension (name As String) As IBlank(Of IWithApply)" />
      <MemberSignature Language="F#" Value="abstract member DefineNewExtension : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply&gt;" Usage="iWithExtension.DefineNewExtension name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Verweisname nach einer Erweiterung.</param>
        <summary>
            Beginn der Definition einer Referenz zur sicherheitseinstellungserweiterung an die virtuellen Computer in der Skalierungsgruppe angefügt werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die erste Stufe der Erweiterung Verweisdefinition.</return>
      </Docs>
    </Member>
    <Member MemberName="UpdateExtension">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.Update.IUpdate UpdateExtension (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.Update.IUpdate UpdateExtension(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithExtension.UpdateExtension(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateExtension (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdateExtension : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.Update.IUpdate" Usage="iWithExtension.UpdateExtension name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Verweisname für die Erweiterung.</param>
        <summary>
            Startet die Beschreibung des ein Update einer vorhandenen Erweiterung, die den virtuellen Computern in der Menge Skalierung zugewiesen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die erste Phase des Updates Verweis Erweiterung.</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutExtension">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply WithoutExtension (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply WithoutExtension(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithExtension.WithoutExtension(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutExtension (name As String) As IWithApply" />
      <MemberSignature Language="F#" Value="abstract member WithoutExtension : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply" Usage="iWithExtension.WithoutExtension name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Verweisname der Erweiterung entfernt/deinstalliert werden.</param>
        <summary>
            Entfernt die Erweiterung mit dem angegebenen Namen aus den virtuellen Computern in der Menge der Skala an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
  </Members>
</Type>