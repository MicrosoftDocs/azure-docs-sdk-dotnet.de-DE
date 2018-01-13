<Type Name="IWithUnmanagedDataDisk" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithUnmanagedDataDisk">
  <TypeSignature Language="C#" Value="public interface IWithUnmanagedDataDisk" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithUnmanagedDataDisk" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithUnmanagedDataDisk" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithUnmanagedDataDisk" />
  <TypeSignature Language="F#" Value="type IWithUnmanagedDataDisk = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase der Definition eines virtuellen Computers ermöglicht, eine nicht verwaltete Datenträger hinzu.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineUnmanagedDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IBlank&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithUnmanagedCreate&gt; DefineUnmanagedDataDisk (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IBlank`1&lt;class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithUnmanagedCreate&gt; DefineUnmanagedDataDisk(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithUnmanagedDataDisk.DefineUnmanagedDataDisk(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineUnmanagedDataDisk (name As String) As IBlank(Of IWithUnmanagedCreate)" />
      <MemberSignature Language="F#" Value="abstract member DefineUnmanagedDataDisk : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IBlank&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithUnmanagedCreate&gt;" Usage="iWithUnmanagedDataDisk.DefineUnmanagedDataDisk name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IBlank&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithUnmanagedCreate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name für den Datenträger.</param>
        <summary>
            Startet die Definition von einem nicht verwalteten Datenträger an den virtuellen Computer angefügt werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die erste Phase der Definition einer nicht verwalteten Daten-Datenträger.</return>
      </Docs>
    </Member>
    <Member MemberName="WithExistingUnmanagedDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithUnmanagedCreate WithExistingUnmanagedDataDisk (string storageAccountName, string containerName, string vhdName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithUnmanagedCreate WithExistingUnmanagedDataDisk(string storageAccountName, string containerName, string vhdName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithUnmanagedDataDisk.WithExistingUnmanagedDataDisk(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingUnmanagedDataDisk (storageAccountName As String, containerName As String, vhdName As String) As IWithUnmanagedCreate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingUnmanagedDataDisk : string * string * string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithUnmanagedCreate" Usage="iWithUnmanagedDataDisk.WithExistingUnmanagedDataDisk (storageAccountName, containerName, vhdName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithUnmanagedCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="vhdName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="storageAccountName">Name des Speicherkontos.</param>
        <param name="containerName">Der Name des Containers, halten die VHD-Datei.</param>
        <param name="vhdName">Der Name für die VHD-Datei.</param>
        <summary>
            Fügt eine vorhandene nicht verwalteten VHD als Datenträger für Daten mit dem virtuellen Computer an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewUnmanagedDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithUnmanagedCreate WithNewUnmanagedDataDisk (int sizeInGB);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithUnmanagedCreate WithNewUnmanagedDataDisk(int32 sizeInGB) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithUnmanagedDataDisk.WithNewUnmanagedDataDisk(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewUnmanagedDataDisk (sizeInGB As Integer) As IWithUnmanagedCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewUnmanagedDataDisk : int -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithUnmanagedCreate" Usage="iWithUnmanagedDataDisk.WithNewUnmanagedDataDisk sizeInGB" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithUnmanagedCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sizeInGB" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="sizeInGB">Die Größe des Datenträgers in GB.</param>
        <summary>
            Fügt einen neuen leeren nicht verwalteten Datenträger mit dem virtuellen Computer an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>