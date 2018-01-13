<Type Name="IWithManagedDataDisk" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithManagedDataDisk">
  <TypeSignature Language="C#" Value="public interface IWithManagedDataDisk" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithManagedDataDisk" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithManagedDataDisk" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithManagedDataDisk" />
  <TypeSignature Language="F#" Value="type IWithManagedDataDisk = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Stufe der ein Update der virtuellen Maschine an einen verwalteten Datenträger zu ermöglichen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithExistingDataDisk (Microsoft.Azure.Management.Compute.Fluent.IDisk disk);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithExistingDataDisk(class Microsoft.Azure.Management.Compute.Fluent.IDisk disk) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithManagedDataDisk.WithExistingDataDisk(Microsoft.Azure.Management.Compute.Fluent.IDisk)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingDataDisk (disk As IDisk) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingDataDisk : Microsoft.Azure.Management.Compute.Fluent.IDisk -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate" Usage="iWithManagedDataDisk.WithExistingDataDisk disk" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disk" Type="Microsoft.Azure.Management.Compute.Fluent.IDisk" />
      </Parameters>
      <Docs>
        <param name="disk">Ein verwalteter Datenträger.</param>
        <summary>
            Ordnet einem vorhandenen verwalteten Quelldatenträger mit dem virtuellen Computer an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithExistingDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithExistingDataDisk (Microsoft.Azure.Management.Compute.Fluent.IDisk disk, int lun, Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithExistingDataDisk(class Microsoft.Azure.Management.Compute.Fluent.IDisk disk, int32 lun, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithManagedDataDisk.WithExistingDataDisk(Microsoft.Azure.Management.Compute.Fluent.IDisk,System.Int32,Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingDataDisk (disk As IDisk, lun As Integer, cachingType As CachingTypes) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingDataDisk : Microsoft.Azure.Management.Compute.Fluent.IDisk * int * Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate" Usage="iWithManagedDataDisk.WithExistingDataDisk (disk, lun, cachingType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disk" Type="Microsoft.Azure.Management.Compute.Fluent.IDisk" />
        <Parameter Name="lun" Type="System.Int32" />
        <Parameter Name="cachingType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes" />
      </Parameters>
      <Docs>
        <param name="disk">Der verwaltete Datenträger.</param>
        <param name="lun">Der Datenträger-LUN.</param>
        <param name="cachingType">ein Zwischenspeichern Typ.</param>
        <summary>
            Gibt eine vorhandene verwaltet Quelldatenträger und Einstellungen an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithExistingDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithExistingDataDisk (Microsoft.Azure.Management.Compute.Fluent.IDisk disk, int newSizeInGB, int lun, Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithExistingDataDisk(class Microsoft.Azure.Management.Compute.Fluent.IDisk disk, int32 newSizeInGB, int32 lun, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithManagedDataDisk.WithExistingDataDisk(Microsoft.Azure.Management.Compute.Fluent.IDisk,System.Int32,System.Int32,Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingDataDisk (disk As IDisk, newSizeInGB As Integer, lun As Integer, cachingType As CachingTypes) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingDataDisk : Microsoft.Azure.Management.Compute.Fluent.IDisk * int * int * Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate" Usage="iWithManagedDataDisk.WithExistingDataDisk (disk, newSizeInGB, lun, cachingType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disk" Type="Microsoft.Azure.Management.Compute.Fluent.IDisk" />
        <Parameter Name="newSizeInGB" Type="System.Int32" />
        <Parameter Name="lun" Type="System.Int32" />
        <Parameter Name="cachingType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes" />
      </Parameters>
      <Docs>
        <param name="disk">Ein verwalteter Datenträger.</param>
        <param name="newSizeInGB">Der Datenträger ändern Sie die Größe in GB Größe.</param>
        <param name="lun">Der Datenträger-LUN.</param>
        <param name="cachingType">ein Zwischenspeichern Typ.</param>
        <summary>
            Gibt eine vorhandene verwaltet Quelldatenträger und Einstellungen an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithNewDataDisk (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Compute.Fluent.IDisk&gt; creatable);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithNewDataDisk(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IDisk&gt; creatable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithManagedDataDisk.WithNewDataDisk(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{Microsoft.Azure.Management.Compute.Fluent.IDisk})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewDataDisk (creatable As ICreatable(Of IDisk)) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewDataDisk : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Compute.Fluent.IDisk&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate" Usage="iWithManagedDataDisk.WithNewDataDisk creatable" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="creatable" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Compute.Fluent.IDisk&gt;" />
      </Parameters>
      <Docs>
        <param name="creatable">Die Definition einer erstellbaren Datenträger.</param>
        <summary>
            Gibt an, dass ein verwalteter Datenträger muss explizit mit der angegebenen Definition erstellt und mit dem virtuellen Computer als Datenträger angefügt werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithNewDataDisk (int sizeInGB);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithNewDataDisk(int32 sizeInGB) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithManagedDataDisk.WithNewDataDisk(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewDataDisk (sizeInGB As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewDataDisk : int -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate" Usage="iWithManagedDataDisk.WithNewDataDisk sizeInGB" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate</ReturnType>
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
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithNewDataDisk (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Compute.Fluent.IDisk&gt; creatable, int lun, Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithNewDataDisk(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IDisk&gt; creatable, int32 lun, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithManagedDataDisk.WithNewDataDisk(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{Microsoft.Azure.Management.Compute.Fluent.IDisk},System.Int32,Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewDataDisk (creatable As ICreatable(Of IDisk), lun As Integer, cachingType As CachingTypes) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewDataDisk : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Compute.Fluent.IDisk&gt; * int * Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate" Usage="iWithManagedDataDisk.WithNewDataDisk (creatable, lun, cachingType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="creatable" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Compute.Fluent.IDisk&gt;" />
        <Parameter Name="lun" Type="System.Int32" />
        <Parameter Name="cachingType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes" />
      </Parameters>
      <Docs>
        <param name="creatable">Die Definition einer erstellbaren Datenträger.</param>
        <param name="lun">Der Datenträger LUN.</param>
        <param name="cachingType">Ein Datenträger Zwischenspeichern Typ.</param>
        <summary>
            Gibt an, dass ein verwalteter Datenträger muss explizit mit der angegebenen Definition erstellt und mit dem virtuellen Computer als Datenträger angefügt werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithNewDataDisk (int sizeInGB, int lun, Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithNewDataDisk(int32 sizeInGB, int32 lun, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithManagedDataDisk.WithNewDataDisk(System.Int32,System.Int32,Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewDataDisk (sizeInGB As Integer, lun As Integer, cachingType As CachingTypes) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewDataDisk : int * int * Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate" Usage="iWithManagedDataDisk.WithNewDataDisk (sizeInGB, lun, cachingType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sizeInGB" Type="System.Int32" />
        <Parameter Name="lun" Type="System.Int32" />
        <Parameter Name="cachingType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes" />
      </Parameters>
      <Docs>
        <param name="sizeInGB">Die Größe des verwalteten Datenträgers.</param>
        <param name="lun">Der Datenträger-LUN.</param>
        <param name="cachingType">ein Zwischenspeichern Typ.</param>
        <summary>
            Gibt an, dass es sich bei ein verwalteter Datenträger mit den angegebenen Einstellungen implizit erstellt werden muss.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithNewDataDisk (int sizeInGB, int lun, Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType, Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes storageAccountType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithNewDataDisk(int32 sizeInGB, int32 lun, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes storageAccountType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithManagedDataDisk.WithNewDataDisk(System.Int32,System.Int32,Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes,Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewDataDisk (sizeInGB As Integer, lun As Integer, cachingType As CachingTypes, storageAccountType As StorageAccountTypes) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewDataDisk : int * int * Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes * Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate" Usage="iWithManagedDataDisk.WithNewDataDisk (sizeInGB, lun, cachingType, storageAccountType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate</ReturnType>
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
        <param name="cachingType">ein Zwischenspeichern Typ.</param>
        <param name="storageAccountType">Ein Speicher-Kontotyp.</param>
        <summary>
            Gibt an, dass es sich bei ein verwalteter Datenträger mit den angegebenen Einstellungen implizit erstellt werden muss.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithoutDataDisk (int lun);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithoutDataDisk(int32 lun) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithManagedDataDisk.WithoutDataDisk(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutDataDisk (lun As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutDataDisk : int -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate" Usage="iWithManagedDataDisk.WithoutDataDisk lun" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lun" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="lun">Der Datenträger-LUN.</param>
        <summary>
            Trennt einen verwaltete Datenträger mit der angegebenen LUN vom virtuellen Computer an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
  </Members>
</Type>