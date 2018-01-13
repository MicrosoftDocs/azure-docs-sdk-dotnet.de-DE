<Type Name="IWithManagedDataDisk" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedDataDisk">
  <TypeSignature Language="C#" Value="public interface IWithManagedDataDisk" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithManagedDataDisk" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedDataDisk" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithManagedDataDisk" />
  <TypeSignature Language="F#" Value="type IWithManagedDataDisk = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase der Definition eines virtuellen Computers an einen verwalteten Datenträger ermöglichen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithExistingDataDisk (Microsoft.Azure.Management.Compute.Fluent.IDisk disk);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithExistingDataDisk(class Microsoft.Azure.Management.Compute.Fluent.IDisk disk) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedDataDisk.WithExistingDataDisk(Microsoft.Azure.Management.Compute.Fluent.IDisk)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingDataDisk (disk As IDisk) As IWithManagedCreate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingDataDisk : Microsoft.Azure.Management.Compute.Fluent.IDisk -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate" Usage="iWithManagedDataDisk.WithExistingDataDisk disk" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disk" Type="Microsoft.Azure.Management.Compute.Fluent.IDisk" />
      </Parameters>
      <Docs>
        <param name="disk">Einen vorhandenen verwalteten Datenträger.</param>
        <summary>
            Ordnet einem vorhandenen verwalteten Quelldatenträger mit dem virtuellen Computer an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithExistingDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithExistingDataDisk (Microsoft.Azure.Management.Compute.Fluent.IDisk disk, int lun, Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithExistingDataDisk(class Microsoft.Azure.Management.Compute.Fluent.IDisk disk, int32 lun, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedDataDisk.WithExistingDataDisk(Microsoft.Azure.Management.Compute.Fluent.IDisk,System.Int32,Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingDataDisk (disk As IDisk, lun As Integer, cachingType As CachingTypes) As IWithManagedCreate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingDataDisk : Microsoft.Azure.Management.Compute.Fluent.IDisk * int * Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate" Usage="iWithManagedDataDisk.WithExistingDataDisk (disk, lun, cachingType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disk" Type="Microsoft.Azure.Management.Compute.Fluent.IDisk" />
        <Parameter Name="lun" Type="System.Int32" />
        <Parameter Name="cachingType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes" />
      </Parameters>
      <Docs>
        <param name="disk">Ein verwalteter Datenträger.</param>
        <param name="lun">Der Datenträger-LUN.</param>
        <param name="cachingType">ein Zwischenspeichern Typ.</param>
        <summary>
            Ordnet einem vorhandenen verwalteten Quelldatenträger mit dem virtuellen Computer, und gibt zusätzliche Einstellungen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithExistingDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithExistingDataDisk (Microsoft.Azure.Management.Compute.Fluent.IDisk disk, int newSizeInGB, int lun, Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithExistingDataDisk(class Microsoft.Azure.Management.Compute.Fluent.IDisk disk, int32 newSizeInGB, int32 lun, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedDataDisk.WithExistingDataDisk(Microsoft.Azure.Management.Compute.Fluent.IDisk,System.Int32,System.Int32,Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingDataDisk (disk As IDisk, newSizeInGB As Integer, lun As Integer, cachingType As CachingTypes) As IWithManagedCreate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingDataDisk : Microsoft.Azure.Management.Compute.Fluent.IDisk * int * int * Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate" Usage="iWithManagedDataDisk.WithExistingDataDisk (disk, newSizeInGB, lun, cachingType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate</ReturnType>
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
            Ordnet einem vorhandenen verwalteten Quelldatenträger mit dem virtuellen Computer, und gibt zusätzliche Einstellungen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithNewDataDisk (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Compute.Fluent.IDisk&gt; creatable);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithNewDataDisk(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IDisk&gt; creatable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedDataDisk.WithNewDataDisk(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{Microsoft.Azure.Management.Compute.Fluent.IDisk})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewDataDisk (creatable As ICreatable(Of IDisk)) As IWithManagedCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewDataDisk : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Compute.Fluent.IDisk&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate" Usage="iWithManagedDataDisk.WithNewDataDisk creatable" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="creatable" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Compute.Fluent.IDisk&gt;" />
      </Parameters>
      <Docs>
        <param name="creatable">Die Definition einer erstellbaren Datenträger.</param>
        <summary>
            Gibt an, dass ein verwalteter Datenträger mit der angegebenen Definition explizit erstellt und mit dem virtuellen Computer als Datenträger angefügt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithNewDataDisk (int sizeInGB);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithNewDataDisk(int32 sizeInGB) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedDataDisk.WithNewDataDisk(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewDataDisk (sizeInGB As Integer) As IWithManagedCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewDataDisk : int -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate" Usage="iWithManagedDataDisk.WithNewDataDisk sizeInGB" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sizeInGB" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="sizeInGB">Die Größe des verwalteten Datenträgers in GB.</param>
        <summary>
            Gibt an, dass es sich bei ein verwalteter Datenträger mit der angegebenen Größe implizit erstellt werden muss.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithNewDataDisk (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Compute.Fluent.IDisk&gt; creatable, int lun, Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithNewDataDisk(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IDisk&gt; creatable, int32 lun, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedDataDisk.WithNewDataDisk(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{Microsoft.Azure.Management.Compute.Fluent.IDisk},System.Int32,Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewDataDisk (creatable As ICreatable(Of IDisk), lun As Integer, cachingType As CachingTypes) As IWithManagedCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewDataDisk : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Compute.Fluent.IDisk&gt; * int * Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate" Usage="iWithManagedDataDisk.WithNewDataDisk (creatable, lun, cachingType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="creatable" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Compute.Fluent.IDisk&gt;" />
        <Parameter Name="lun" Type="System.Int32" />
        <Parameter Name="cachingType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes" />
      </Parameters>
      <Docs>
        <param name="creatable">Ein erstellbar Datenträger.</param>
        <param name="lun">Der Datenträger LUN.</param>
        <param name="cachingType">Ein Datenträger Zwischenspeichern Typ.</param>
        <summary>
            Gibt an, dass es sich bei ein verwalteter Datenträger muss explizit mit der angegebenen Definition erstellt werden und mit dem virtuellen Computer als Datenträger anfügen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithNewDataDisk (int sizeInGB, int lun, Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithNewDataDisk(int32 sizeInGB, int32 lun, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedDataDisk.WithNewDataDisk(System.Int32,System.Int32,Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewDataDisk (sizeInGB As Integer, lun As Integer, cachingType As CachingTypes) As IWithManagedCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewDataDisk : int * int * Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate" Usage="iWithManagedDataDisk.WithNewDataDisk (sizeInGB, lun, cachingType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sizeInGB" Type="System.Int32" />
        <Parameter Name="lun" Type="System.Int32" />
        <Parameter Name="cachingType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes" />
      </Parameters>
      <Docs>
        <param name="sizeInGB">Die Größe des verwalteten Datenträgers in GB.</param>
        <param name="lun">Der Datenträger-LUN.</param>
        <param name="cachingType">Der caching-Typ.</param>
        <summary>
            Gibt an, dass es sich bei ein verwalteter Datenträger mit den angegebenen Einstellungen implizit erstellt werden muss.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithNewDataDisk (int sizeInGB, int lun, Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType, Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes storageAccountType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithNewDataDisk(int32 sizeInGB, int32 lun, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes storageAccountType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedDataDisk.WithNewDataDisk(System.Int32,System.Int32,Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes,Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewDataDisk (sizeInGB As Integer, lun As Integer, cachingType As CachingTypes, storageAccountType As StorageAccountTypes) As IWithManagedCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewDataDisk : int * int * Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes * Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate" Usage="iWithManagedDataDisk.WithNewDataDisk (sizeInGB, lun, cachingType, storageAccountType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sizeInGB" Type="System.Int32" />
        <Parameter Name="lun" Type="System.Int32" />
        <Parameter Name="cachingType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes" />
        <Parameter Name="storageAccountType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes" />
      </Parameters>
      <Docs>
        <param name="sizeInGB">Die Größe des verwalteten Datenträgers in GB.</param>
        <param name="lun">Der Datenträger-LUN.</param>
        <param name="cachingType">Der caching-Typ.</param>
        <param name="storageAccountType">Der speicherkontotyp.</param>
        <summary>
            Gibt an, dass es sich bei ein verwalteter Datenträger mit den angegebenen Einstellungen implizit erstellt werden muss.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewDataDiskFromImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithNewDataDiskFromImage (int imageLun);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithNewDataDiskFromImage(int32 imageLun) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedDataDisk.WithNewDataDiskFromImage(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewDataDiskFromImage (imageLun As Integer) As IWithManagedCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewDataDiskFromImage : int -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate" Usage="iWithManagedDataDisk.WithNewDataDiskFromImage imageLun" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="imageLun" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="imageLun">Die LUN des Quellbilds für den Datenträger.</param>
        <summary>
            Gibt an, der den Datenträger aus der Daten-Datenträger-Imagedatei in Image des virtuellen Computers erstellt werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewDataDiskFromImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithNewDataDiskFromImage (int imageLun, int newSizeInGB, Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithNewDataDiskFromImage(int32 imageLun, int32 newSizeInGB, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedDataDisk.WithNewDataDiskFromImage(System.Int32,System.Int32,Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewDataDiskFromImage (imageLun As Integer, newSizeInGB As Integer, cachingType As CachingTypes) As IWithManagedCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewDataDiskFromImage : int * int * Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate" Usage="iWithManagedDataDisk.WithNewDataDiskFromImage (imageLun, newSizeInGB, cachingType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="imageLun" Type="System.Int32" />
        <Parameter Name="newSizeInGB" Type="System.Int32" />
        <Parameter Name="cachingType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes" />
      </Parameters>
      <Docs>
        <param name="imageLun">Die LUN des Quellbilds für den Datenträger.</param>
        <param name="newSizeInGB">Die neue Größe, die die Standardgröße angegeben, in der Daten-Datenträger-Imagedatei überschreibt.</param>
        <param name="cachingType">ein Zwischenspeichern Typ.</param>
        <summary>
            Gibt an, der den Datenträger aus der Daten-Datenträger-Imagedatei in Image des virtuellen Computers erstellt werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewDataDiskFromImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithNewDataDiskFromImage (int imageLun, int newSizeInGB, Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType, Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes storageAccountType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithNewDataDiskFromImage(int32 imageLun, int32 newSizeInGB, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes storageAccountType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedDataDisk.WithNewDataDiskFromImage(System.Int32,System.Int32,Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes,Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewDataDiskFromImage (imageLun As Integer, newSizeInGB As Integer, cachingType As CachingTypes, storageAccountType As StorageAccountTypes) As IWithManagedCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewDataDiskFromImage : int * int * Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes * Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate" Usage="iWithManagedDataDisk.WithNewDataDiskFromImage (imageLun, newSizeInGB, cachingType, storageAccountType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="imageLun" Type="System.Int32" />
        <Parameter Name="newSizeInGB" Type="System.Int32" />
        <Parameter Name="cachingType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes" />
        <Parameter Name="storageAccountType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes" />
      </Parameters>
      <Docs>
        <param name="imageLun">Die LUN des Quellbilds für den Datenträger.</param>
        <param name="newSizeInGB">Die neue Größe, die die Standardgröße angegeben, in der Daten-Datenträger-Imagedatei überschreibt.</param>
        <param name="cachingType">ein Zwischenspeichern Typ.</param>
        <param name="storageAccountType">Ein Speicher-Kontotyp.</param>
        <summary>
            Gibt an, der den Datenträger aus der Daten-Datenträger-Imagedatei in Image des virtuellen Computers erstellt werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>