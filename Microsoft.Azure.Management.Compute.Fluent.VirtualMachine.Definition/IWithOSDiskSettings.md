<Type Name="IWithOSDiskSettings" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOSDiskSettings">
  <TypeSignature Language="C#" Value="public interface IWithOSDiskSettings" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithOSDiskSettings" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOSDiskSettings" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithOSDiskSettings" />
  <TypeSignature Language="F#" Value="type IWithOSDiskSettings = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase der Definition eines virtuellen Computers, sodass Konfigurationen der Betriebssystem-Datenträger angeben.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithOSDiskCaching">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithOSDiskCaching (Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithOSDiskCaching(valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOSDiskSettings.WithOSDiskCaching(Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithOSDiskCaching (cachingType As CachingTypes) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithOSDiskCaching : Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate" Usage="iWithOSDiskSettings.WithOSDiskCaching cachingType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cachingType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes" />
      </Parameters>
      <Docs>
        <param name="cachingType">ein Zwischenspeichern Typ.</param>
        <summary>
            Gibt an, welche Zwischenspeichern für den Betriebssystem-Datenträger.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithOSDiskEncryptionSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithOSDiskEncryptionSettings (Microsoft.Azure.Management.Compute.Fluent.Models.DiskEncryptionSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithOSDiskEncryptionSettings(class Microsoft.Azure.Management.Compute.Fluent.Models.DiskEncryptionSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOSDiskSettings.WithOSDiskEncryptionSettings(Microsoft.Azure.Management.Compute.Fluent.Models.DiskEncryptionSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithOSDiskEncryptionSettings (settings As DiskEncryptionSettings) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithOSDiskEncryptionSettings : Microsoft.Azure.Management.Compute.Fluent.Models.DiskEncryptionSettings -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate" Usage="iWithOSDiskSettings.WithOSDiskEncryptionSettings settings" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="settings" Type="Microsoft.Azure.Management.Compute.Fluent.Models.DiskEncryptionSettings" />
      </Parameters>
      <Docs>
        <param name="settings">die verschlüsselungseinstellungen.</param>
        <summary>
            Gibt die Einstellungen für die Verschlüsselung für den Betriebssystem-Datenträger an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithOSDiskName">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithOSDiskName (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithOSDiskName(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOSDiskSettings.WithOSDiskName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithOSDiskName (name As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithOSDiskName : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate" Usage="iWithOSDiskSettings.WithOSDiskName name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Ein Name für den Betriebssystem-Datenträger.</param>
        <summary>
            Gibt den Namen für den Betriebssystem-Datenträger.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithOSDiskSizeInGB">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithOSDiskSizeInGB (int size);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithOSDiskSizeInGB(int32 size) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOSDiskSettings.WithOSDiskSizeInGB(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithOSDiskSizeInGB (size As Integer) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithOSDiskSizeInGB : int -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate" Usage="iWithOSDiskSettings.WithOSDiskSizeInGB size" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="size" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="size">Die VHD-Größe.</param>
        <summary>
            Gibt die Größe des OSDisk in GB an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>