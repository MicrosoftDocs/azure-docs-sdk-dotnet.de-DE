<Type Name="IWithUnmanagedDataDisk" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithUnmanagedDataDisk">
  <TypeSignature Language="C#" Value="public interface IWithUnmanagedDataDisk" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithUnmanagedDataDisk" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithUnmanagedDataDisk" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithUnmanagedDataDisk" />
  <TypeSignature Language="F#" Value="type IWithUnmanagedDataDisk = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Stufe der eine virtuelle Maschine Definition ermöglicht Datenträgerkonfiguration nicht verwaltete Daten angeben.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineUnmanagedDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate&gt; DefineUnmanagedDataDisk (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate&gt; DefineUnmanagedDataDisk(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithUnmanagedDataDisk.DefineUnmanagedDataDisk(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineUnmanagedDataDisk (name As String) As IBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineUnmanagedDataDisk : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate&gt;" Usage="iWithUnmanagedDataDisk.DefineUnmanagedDataDisk name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name für den Datenträger.</param>
        <summary>
            Beginn der Definition eines leer nicht verwalteten Datenträgers an den virtuellen Computer zusammen mit seiner Konfiguration zugeordnet werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die erste Phase der Definition des Daten-Datenträger.</return>
      </Docs>
    </Member>
    <Member MemberName="UpdateUnmanagedDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Update.IUpdate UpdateUnmanagedDataDisk (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Update.IUpdate UpdateUnmanagedDataDisk(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithUnmanagedDataDisk.UpdateUnmanagedDataDisk(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateUnmanagedDataDisk (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdateUnmanagedDataDisk : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Update.IUpdate" Usage="iWithUnmanagedDataDisk.UpdateUnmanagedDataDisk name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name eines vorhandenen Datenträgers.</param>
        <summary>
            Startet die Beschreibung eines Updates für einen vorhandenen nicht verwalteten Datenträger dieses virtuellen Computers an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die erste Phase des Daten-Datenträger-Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithExistingUnmanagedDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithExistingUnmanagedDataDisk (string storageAccountName, string containerName, string vhdName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithExistingUnmanagedDataDisk(string storageAccountName, string containerName, string vhdName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithUnmanagedDataDisk.WithExistingUnmanagedDataDisk(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingUnmanagedDataDisk (storageAccountName As String, containerName As String, vhdName As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingUnmanagedDataDisk : string * string * string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate" Usage="iWithUnmanagedDataDisk.WithExistingUnmanagedDataDisk (storageAccountName, containerName, vhdName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="vhdName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="storageAccountName">Der Name des Speicherkontos.</param>
        <param name="containerName">Der Name des Containers, halten die VHD-Datei.</param>
        <param name="vhdName">Der Name für die VHD-Datei.</param>
        <summary>
            Gibt an, einer vorhandenen virtuellen Festplatte, die mit dem virtuellen Computer als Datenträger angefügt werden muss.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die Phase, die Definition des erstellbar virtuellen Computer darstellt.</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewUnmanagedDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithNewUnmanagedDataDisk (int sizeInGB);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithNewUnmanagedDataDisk(int32 sizeInGB) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithUnmanagedDataDisk.WithNewUnmanagedDataDisk(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewUnmanagedDataDisk (sizeInGB As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewUnmanagedDataDisk : int -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate" Usage="iWithUnmanagedDataDisk.WithNewUnmanagedDataDisk sizeInGB" />
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
        <param name="sizeInGB">Die Größe des Datenträgers in GB.</param>
        <summary>
            Gibt an, dass ein neuer leerer nicht verwalteten Datenträger an den virtuellen Computer angefügt werden muss.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die Phase, die Definition des erstellbar virtuellen Computer darstellt.</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutUnmanagedDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithoutUnmanagedDataDisk (int lun);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithoutUnmanagedDataDisk(int32 lun) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithUnmanagedDataDisk.WithoutUnmanagedDataDisk(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutUnmanagedDataDisk (lun As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutUnmanagedDataDisk : int -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate" Usage="iWithUnmanagedDataDisk.WithoutUnmanagedDataDisk lun" />
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
        <param name="lun">Die logische Gerätenummer des Datenträgers zu entfernen.</param>
        <summary>
            Trennt einen nicht verwalteten Datenträger vom virtuellen Computer an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutUnmanagedDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithoutUnmanagedDataDisk (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithoutUnmanagedDataDisk(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithUnmanagedDataDisk.WithoutUnmanagedDataDisk(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutUnmanagedDataDisk (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutUnmanagedDataDisk : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate" Usage="iWithUnmanagedDataDisk.WithoutUnmanagedDataDisk name" />
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
        <param name="name">Der Name des einen vorhandenen Datenträger zu entfernen.</param>
        <summary>
            Trennt einen nicht verwalteten Datenträger vom virtuellen Computer an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
  </Members>
</Type>