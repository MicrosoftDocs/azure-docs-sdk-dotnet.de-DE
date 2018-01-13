<Type Name="IWithWindowsCreateUnmanaged" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateUnmanaged">
  <TypeSignature Language="C#" Value="public interface IWithWindowsCreateUnmanaged : Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithUnmanagedCreate, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithWindowsCreateUnmanaged implements class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithBootDiagnostics, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCapacity, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithComputerNamePrefix, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCustomData, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithExtension, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedServiceIdentity, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOSDiskSettings, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOverProvision, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithStorageAccount, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithUnmanagedCreate, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithUnmanagedDataDisk, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithUpgradePolicy, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags`1&lt;class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateUnmanaged" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithWindowsCreateUnmanaged&#xA;Implements IBeta, ICreatable(Of IVirtualMachineScaleSet), IDefinitionWithTags(Of IWithCreate), IWithUnmanagedCreate" />
  <TypeSignature Language="F#" Value="type IWithWindowsCreateUnmanaged = interface&#xA;    interface IWithUnmanagedCreate&#xA;    interface IWithUnmanagedDataDisk&#xA;    interface IWithCreate&#xA;    interface ICreatable&lt;IVirtualMachineScaleSet&gt;&#xA;    interface IIndexable&#xA;    interface IWithOSDiskSettings&#xA;    interface IWithComputerNamePrefix&#xA;    interface IWithCapacity&#xA;    interface IWithUpgradePolicy&#xA;    interface IWithOverProvision&#xA;    interface IWithStorageAccount&#xA;    interface IWithCustomData&#xA;    interface IWithExtension&#xA;    interface IWithManagedServiceIdentity&#xA;    interface IBeta&#xA;    interface IWithBootDiagnostics&#xA;    interface IDefinitionWithTags&lt;IWithCreate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithUnmanagedCreate</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Festlegen des Status von einem Windows-VM-Skalierungsgruppe Definition enthält alle minimale erforderlichen Eingaben für die Ressource erstellt werden, sondern auch für andere optionalen Einstellungen angegeben werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithAutoUpdate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateUnmanaged WithAutoUpdate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateUnmanaged WithAutoUpdate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateUnmanaged.WithAutoUpdate" />
      <MemberSignature Language="VB.NET" Value="Public Function WithAutoUpdate () As IWithWindowsCreateUnmanaged" />
      <MemberSignature Language="F#" Value="abstract member WithAutoUpdate : unit -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateUnmanaged" Usage="iWithWindowsCreateUnmanaged.WithAutoUpdate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateUnmanaged</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Automatische Updates aktiviert.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutAutoUpdate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateUnmanaged WithoutAutoUpdate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateUnmanaged WithoutAutoUpdate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateUnmanaged.WithoutAutoUpdate" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutAutoUpdate () As IWithWindowsCreateUnmanaged" />
      <MemberSignature Language="F#" Value="abstract member WithoutAutoUpdate : unit -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateUnmanaged" Usage="iWithWindowsCreateUnmanaged.WithoutAutoUpdate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateUnmanaged</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Automatische Updates deaktiviert.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutVMAgent">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateUnmanaged WithoutVMAgent ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateUnmanaged WithoutVMAgent() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateUnmanaged.WithoutVMAgent" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutVMAgent () As IWithWindowsCreateUnmanaged" />
      <MemberSignature Language="F#" Value="abstract member WithoutVMAgent : unit -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateUnmanaged" Usage="iWithWindowsCreateUnmanaged.WithoutVMAgent " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateUnmanaged</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Deaktiviert den VM-Agent an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithTimeZone">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateUnmanaged WithTimeZone (string timeZone);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateUnmanaged WithTimeZone(string timeZone) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateUnmanaged.WithTimeZone(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithTimeZone (timeZone As String) As IWithWindowsCreateUnmanaged" />
      <MemberSignature Language="F#" Value="abstract member WithTimeZone : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateUnmanaged" Usage="iWithWindowsCreateUnmanaged.WithTimeZone timeZone" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateUnmanaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeZone" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="timeZone">Eine Zeitzone.</param>
        <summary>
            Gibt die Zeitzone für den virtuellen Computer verwenden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithVMAgent">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateUnmanaged WithVMAgent ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateUnmanaged WithVMAgent() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateUnmanaged.WithVMAgent" />
      <MemberSignature Language="VB.NET" Value="Public Function WithVMAgent () As IWithWindowsCreateUnmanaged" />
      <MemberSignature Language="F#" Value="abstract member WithVMAgent : unit -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateUnmanaged" Usage="iWithWindowsCreateUnmanaged.WithVMAgent " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateUnmanaged</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Ermöglicht dem VM-Agent.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithWinRM">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateUnmanaged WithWinRM (Microsoft.Azure.Management.Compute.Fluent.Models.WinRMListener listener);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateUnmanaged WithWinRM(class Microsoft.Azure.Management.Compute.Fluent.Models.WinRMListener listener) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateUnmanaged.WithWinRM(Microsoft.Azure.Management.Compute.Fluent.Models.WinRMListener)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithWinRM (listener As WinRMListener) As IWithWindowsCreateUnmanaged" />
      <MemberSignature Language="F#" Value="abstract member WithWinRM : Microsoft.Azure.Management.Compute.Fluent.Models.WinRMListener -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateUnmanaged" Usage="iWithWindowsCreateUnmanaged.WithWinRM listener" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateUnmanaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="listener" Type="Microsoft.Azure.Management.Compute.Fluent.Models.WinRMListener" />
      </Parameters>
      <Docs>
        <param name="listener">Ein WinRM-Listener.</param>
        <summary>
            Gibt den WinRM-Listener.
            Jeder Aufruf dieser Methode fügt den angegebenen Listener zur Liste der WinRM-Listener des virtuellen Computers.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>