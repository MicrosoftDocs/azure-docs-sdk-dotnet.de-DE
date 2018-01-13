<Type Name="IWithNewVhdDiskSettings&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IWithNewVhdDiskSettings&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithNewVhdDiskSettings&lt;ParentT&gt; : Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IWithAttach&lt;ParentT&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Update.IInUpdate&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithNewVhdDiskSettings`1&lt;ParentT&gt; implements class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Update.IInUpdate`1&lt;!ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IWithNewVhdDiskSettings`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithNewVhdDiskSettings(Of ParentT)&#xA;Implements IInUpdate(Of ParentT), IWithAttach(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithNewVhdDiskSettings&lt;'ParentT&gt; = interface&#xA;    interface IWithAttach&lt;'ParentT&gt;&#xA;    interface IInUpdate&lt;'ParentT&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IWithAttach&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Update.IInUpdate&lt;ParentT&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="ParentT">Die Phase des übergeordneten Updates wieder nach dem Anfügen dieser Definition.</typeparam>
    <summary>
            Die Stufe, die ermöglicht konfigurieren Sie den Datenträger basierend auf neuen virtuellen Festplatte.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="StoreAt">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IWithNewVhdDiskSettings&lt;ParentT&gt; StoreAt (string storageAccountName, string containerName, string vhdName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IWithNewVhdDiskSettings`1&lt;!ParentT&gt; StoreAt(string storageAccountName, string containerName, string vhdName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IWithNewVhdDiskSettings`1.StoreAt(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function StoreAt (storageAccountName As String, containerName As String, vhdName As String) As IWithNewVhdDiskSettings(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member StoreAt : string * string * string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IWithNewVhdDiskSettings&lt;'ParentT&gt;" Usage="iWithNewVhdDiskSettings.StoreAt (storageAccountName, containerName, vhdName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IWithNewVhdDiskSettings&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="vhdName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="storageAccountName">Der Name des Speicherkontos.</param>
        <param name="containerName">Der Name des Containers zum Speichern der neuen VHD-Datei.</param>
        <param name="vhdName">Der Name für die neue VHD-Datei.</param>
        <summary>
            Gibt an, in denen die neuer leerer Datenträger zugeordnete VHD-Datei gespeichert werden muss.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase der Datendefinition der Datenträger.</return>
      </Docs>
    </Member>
    <Member MemberName="WithCaching">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IWithNewVhdDiskSettings&lt;ParentT&gt; WithCaching (Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IWithNewVhdDiskSettings`1&lt;!ParentT&gt; WithCaching(valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IWithNewVhdDiskSettings`1.WithCaching(Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithCaching (cachingType As CachingTypes) As IWithNewVhdDiskSettings(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithCaching : Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IWithNewVhdDiskSettings&lt;'ParentT&gt;" Usage="iWithNewVhdDiskSettings.WithCaching cachingType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IWithNewVhdDiskSettings&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cachingType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes" />
      </Parameters>
      <Docs>
        <param name="cachingType">der Datenträger, die caching-Typ. Folgende Werte sind möglich: "None", "ReadOnly", "ReadWrite".</param>
        <summary>
            Gibt an, welche Zwischenspeichern für den Datenträger.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase der Datendefinition der Datenträger.</return>
      </Docs>
    </Member>
    <Member MemberName="WithLun">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IWithNewVhdDiskSettings&lt;ParentT&gt; WithLun (int lun);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IWithNewVhdDiskSettings`1&lt;!ParentT&gt; WithLun(int32 lun) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IWithNewVhdDiskSettings`1.WithLun(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithLun (lun As Integer) As IWithNewVhdDiskSettings(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithLun : int -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IWithNewVhdDiskSettings&lt;'ParentT&gt;" Usage="iWithNewVhdDiskSettings.WithLun lun" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IWithNewVhdDiskSettings&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lun" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="lun">Die logische Gerätenummer.</param>
        <summary>
            Gibt die logische Gerätenummer für den Datenträger an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase der Datendefinition der Datenträger.</return>
      </Docs>
    </Member>
  </Members>
</Type>