<Type Name="TableEncryptionPolicy" FullName="Microsoft.WindowsAzure.Storage.Table.TableEncryptionPolicy">
  <TypeSignature Language="C#" Value="public class TableEncryptionPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TableEncryptionPolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Table.TableEncryptionPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class TableEncryptionPolicy" />
  <TypeSignature Language="F#" Value="type TableEncryptionPolicy = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt eine Verschlüsselungsrichtlinie für das Ausführen von Umschlag Verschlüsselung/Entschlüsselung von Entitäten in Azure-Tabellen dar.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableEncryptionPolicy (Microsoft.Azure.KeyVault.Core.IKey key, Microsoft.Azure.KeyVault.Core.IKeyResolver keyResolver);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.KeyVault.Core.IKey key, class Microsoft.Azure.KeyVault.Core.IKeyResolver keyResolver) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableEncryptionPolicy.#ctor(Microsoft.Azure.KeyVault.Core.IKey,Microsoft.Azure.KeyVault.Core.IKeyResolver)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (key As IKey, keyResolver As IKeyResolver)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Table.TableEncryptionPolicy : Microsoft.Azure.KeyVault.Core.IKey * Microsoft.Azure.KeyVault.Core.IKeyResolver -&gt; Microsoft.WindowsAzure.Storage.Table.TableEncryptionPolicy" Usage="new Microsoft.WindowsAzure.Storage.Table.TableEncryptionPolicy (key, keyResolver)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="key" Type="Microsoft.Azure.KeyVault.Core.IKey" />
        <Parameter Name="keyResolver" Type="Microsoft.Azure.KeyVault.Core.IKeyResolver" />
      </Parameters>
      <Docs>
        <param name="key">Ein Objekt des Typs <see cref="T:Microsoft.Azure.KeyVault.Core.IKey" /> , die die Inhaltsverschlüsselungsschlüssel Wrap/Entpacken von verwendet wird.</param>
        <param name="keyResolver">Der Key-Konfliktlöser verwendet, um den richtigen Schlüssel zum Entschlüsseln der vorhandenen Tabellenentitäten auszuwählen.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableEncryptionPolicy" /> Klasse mit dem angegebenen Schlüssel und den Konfliktlöser.
            </summary>
        <remarks>Ist die generierte Richtlinie für die Verschlüsselung verwendet werden, werden Benutzer geben Sie einen Schlüssel mindestens erwartet.
            Das Fehlen des Schlüssels wird dazu führen, dass eine Ausnahme ausgelöst wird, während der Verschlüsselung.<br />
            Wenn die generierte Richtlinie für die Entschlüsselung verwendet werden soll, können Benutzern Resolvern Schlüssel bereitstellen. Die Clientbibliothek wird:<br />
            1. Rufen Sie die wichtigsten Konfliktlöser, auf, wenn angegeben, um den Schlüssel zu erhalten.<br />
            2. Wenn der Konfliktlöser wird nicht angegeben, aber ein Schlüssel angegeben worden ist, entspricht die Clientbibliothek des Schlüssels ID für die Schlüssel und die Verwendung des Schlüssels.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Key">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.Core.IKey Key { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.Core.IKey Key" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.TableEncryptionPolicy.Key" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Key As IKey" />
      <MemberSignature Language="F#" Value="member this.Key : Microsoft.Azure.KeyVault.Core.IKey" Usage="Microsoft.WindowsAzure.Storage.Table.TableEncryptionPolicy.Key" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.Core.IKey</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ein Objekt des Typs <see cref="T:Microsoft.Azure.KeyVault.Core.IKey" /> , Wrap/des Inhaltsschlüssels während der Verschlüsselung Entpacken von verwendet wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyResolver">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.Core.IKeyResolver KeyResolver { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.Core.IKeyResolver KeyResolver" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.TableEncryptionPolicy.KeyResolver" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property KeyResolver As IKeyResolver" />
      <MemberSignature Language="F#" Value="member this.KeyResolver : Microsoft.Azure.KeyVault.Core.IKeyResolver" Usage="Microsoft.WindowsAzure.Storage.Table.TableEncryptionPolicy.KeyResolver" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.Core.IKeyResolver</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder festlegen den Schlüssel Konfliktlöser verwendet, um den richtigen Schlüssel zum Entschlüsseln der vorhandenen Tabellenentitäten auszuwählen.
            </summary>
        <value>Einen Konfliktlöser, der gibt eine <see cref="T:Microsoft.Azure.KeyVault.Core.IKeyResolver" />, angegebenen ein Schlüssel-ID auf.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>