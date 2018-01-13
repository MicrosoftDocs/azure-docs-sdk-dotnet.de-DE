<Type Name="IWithManagedDataDisk" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithManagedDataDisk">
  <TypeSignature Language="C#" Value="public interface IWithManagedDataDisk" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithManagedDataDisk" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithManagedDataDisk" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithManagedDataDisk" />
  <TypeSignature Language="F#" Value="type IWithManagedDataDisk = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase der VM-Skalierungsgruppe festgelegt Update zugelassen wird, um verwaltete Daten, die Datenträger anzugeben.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithNewDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply WithNewDataDisk (int sizeInGB);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply WithNewDataDisk(int32 sizeInGB) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithManagedDataDisk.WithNewDataDisk(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewDataDisk (sizeInGB As Integer) As IWithApply" />
      <MemberSignature Language="F#" Value="abstract member WithNewDataDisk : int -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply" Usage="iWithManagedDataDisk.WithNewDataDisk sizeInGB" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sizeInGB" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="sizeInGB">Die Größe des verwalteten Datenträgers.</param>
        <summary>
            Gibt an, dass es sich bei ein verwalteter Datenträger mit der angegebenen Größe implizit erstellt werden muss.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase der VM-Skalierungsgruppe Festlegung Update.</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply WithNewDataDisk (int sizeInGB, int lun, Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply WithNewDataDisk(int32 sizeInGB, int32 lun, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithManagedDataDisk.WithNewDataDisk(System.Int32,System.Int32,Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewDataDisk (sizeInGB As Integer, lun As Integer, cachingType As CachingTypes) As IWithApply" />
      <MemberSignature Language="F#" Value="abstract member WithNewDataDisk : int * int * Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply" Usage="iWithManagedDataDisk.WithNewDataDisk (sizeInGB, lun, cachingType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sizeInGB" Type="System.Int32" />
        <Parameter Name="lun" Type="System.Int32" />
        <Parameter Name="cachingType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes" />
      </Parameters>
      <Docs>
        <param name="sizeInGB">Die Größe des verwalteten Datenträgers.</param>
        <param name="lun">Der Datenträger-LUN.</param>
        <param name="cachingType">Der caching-Typ.</param>
        <summary>
            Gibt an, dass es sich bei ein verwalteter Datenträger mit den angegebenen Einstellungen implizit erstellt werden muss.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase der VM-Skalierungsgruppe Festlegung Update.</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply WithNewDataDisk (int sizeInGB, int lun, Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType, Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes storageAccountType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply WithNewDataDisk(int32 sizeInGB, int32 lun, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes storageAccountType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithManagedDataDisk.WithNewDataDisk(System.Int32,System.Int32,Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes,Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewDataDisk (sizeInGB As Integer, lun As Integer, cachingType As CachingTypes, storageAccountType As StorageAccountTypes) As IWithApply" />
      <MemberSignature Language="F#" Value="abstract member WithNewDataDisk : int * int * Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes * Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply" Usage="iWithManagedDataDisk.WithNewDataDisk (sizeInGB, lun, cachingType, storageAccountType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sizeInGB" Type="System.Int32" />
        <Parameter Name="lun" Type="System.Int32" />
        <Parameter Name="cachingType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes" />
        <Parameter Name="storageAccountType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes" />
      </Parameters>
      <Docs>
        <param name="sizeInGB">Die Größe des verwalteten Datenträgers.</param>
        <param name="lun">Der Datenträger-LUN.</param>
        <param name="cachingType">Der caching-Typ.</param>
        <param name="storageAccountType">Der speicherkontotyp.</param>
        <summary>
            Gibt an, dass es sich bei ein verwalteter Datenträger mit den angegebenen Einstellungen implizit erstellt werden muss.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase der VM-Skalierungsgruppe Festlegung Update.</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply WithoutDataDisk (int lun);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply WithoutDataDisk(int32 lun) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithManagedDataDisk.WithoutDataDisk(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutDataDisk (lun As Integer) As IWithApply" />
      <MemberSignature Language="F#" Value="abstract member WithoutDataDisk : int -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply" Usage="iWithManagedDataDisk.WithoutDataDisk lun" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lun" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="lun">Der Datenträger-LUN.</param>
        <summary>
            Trennt verwalteten Datenträger mit der angegebenen LUN von Instanzen der virtuellen Maschine Skalierung-Satz.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase der VM-Skalierungsgruppe Festlegung Update.</return>
      </Docs>
    </Member>
  </Members>
</Type>