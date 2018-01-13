<Type Name="IWithStorageAccount" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithStorageAccount">
  <TypeSignature Language="C#" Value="public interface IWithStorageAccount" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithStorageAccount" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithStorageAccount" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithStorageAccount" />
  <TypeSignature Language="F#" Value="type IWithStorageAccount = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase der Definition eines virtuellen Computers zulassen an ein Speicherkonto angeben.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingStorageAccount">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithExistingStorageAccount (Microsoft.Azure.Management.Storage.Fluent.IStorageAccount storageAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithExistingStorageAccount(class Microsoft.Azure.Management.Storage.Fluent.IStorageAccount storageAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithStorageAccount.WithExistingStorageAccount(Microsoft.Azure.Management.Storage.Fluent.IStorageAccount)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingStorageAccount (storageAccount As IStorageAccount) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingStorageAccount : Microsoft.Azure.Management.Storage.Fluent.IStorageAccount -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate" Usage="iWithStorageAccount.WithExistingStorageAccount storageAccount" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="storageAccount" Type="Microsoft.Azure.Management.Storage.Fluent.IStorageAccount" />
      </Parameters>
      <Docs>
        <param name="storageAccount">Ein vorhandenes Speicherkonto.</param>
        <summary>
            Gibt ein vorhandenes Speicherkonto zum Einfügen einer VM Betriebssystem und die Datenträger in VHD.
            In diesem Speicherkonto wird ein Betriebssystem-Datenträger, die basierend auf einem Markt oder einem benutzerimage (generalisierten Image) gespeichert werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewStorageAccount">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithNewStorageAccount (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Storage.Fluent.IStorageAccount&gt; creatable);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithNewStorageAccount(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Storage.Fluent.IStorageAccount&gt; creatable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithStorageAccount.WithNewStorageAccount(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{Microsoft.Azure.Management.Storage.Fluent.IStorageAccount})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewStorageAccount (creatable As ICreatable(Of IStorageAccount)) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewStorageAccount : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Storage.Fluent.IStorageAccount&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate" Usage="iWithStorageAccount.WithNewStorageAccount creatable" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="creatable" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Storage.Fluent.IStorageAccount&gt;" />
      </Parameters>
      <Docs>
        <param name="creatable">Die Definition einer erstellbaren Storage-Konto.</param>
        <summary>
            Gibt die Definition der noch nicht erstellt Speicherkontos zum Einfügen von Betriebssystem und die Daten des virtuellen Computers auf den Datenträger VHDs in.
            Nur die Betriebssystem-Datenträger, die auf Grundlage eines Marketplace-Images werden in das neue Speicherkonto gespeichert.
            Ein Betriebssystem-Datenträger, die basierend auf einem benutzerimage wird in dasselbe Speicherkonto wie das Bild Benutzer gespeichert werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewStorageAccount">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithNewStorageAccount (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithNewStorageAccount(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithStorageAccount.WithNewStorageAccount(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewStorageAccount (name As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewStorageAccount : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate" Usage="iWithStorageAccount.WithNewStorageAccount name" />
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
        <param name="name">Der Name für ein neues Speicherkonto.</param>
        <summary>
            Gibt den Namen eines neuen Speicherkontos Ablegen von Betriebssystem und die Daten des virtuellen Computers auf den Datenträger in VHD.
            Nur ein Betriebssystemdatenträger, basierend auf einem Marketplace-Image wird in das neue Speicherkonto gespeichert werden.
            Ein Betriebssystem-Datenträger, die basierend auf einem benutzerimage wird in dasselbe Speicherkonto wie das Bild Benutzer gespeichert werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>