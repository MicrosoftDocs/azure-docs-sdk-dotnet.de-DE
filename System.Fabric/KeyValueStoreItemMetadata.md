<Type Name="KeyValueStoreItemMetadata" FullName="System.Fabric.KeyValueStoreItemMetadata">
  <TypeSignature Language="C#" Value="public sealed class KeyValueStoreItemMetadata" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit KeyValueStoreItemMetadata extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.KeyValueStoreItemMetadata" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class KeyValueStoreItemMetadata" />
  <TypeSignature Language="F#" Value="type KeyValueStoreItemMetadata = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>Stellt die Metadaten, die zugeordnet sind ein <see cref="T:System.Fabric.KeyValueStoreItem" /> Objekt im Schlüssel/Wert-Speicher.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Key">
      <MemberSignature Language="C#" Value="public string Key { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Key" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.KeyValueStoreItemMetadata.Key" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Key As String" />
      <MemberSignature Language="F#" Value="member this.Key : string" Usage="System.Fabric.KeyValueStoreItemMetadata.Key" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Schlüssel des zugeordneten <see cref="T:System.Fabric.KeyValueStoreItem" /> Objekt.</para>
        </summary>
        <value>
          <para>Ein <see cref="T:System.String" /> , die die Schlüssel des darstellt der <see cref="T:System.Fabric.KeyValueStoreItem" /> Objekt.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModifiedOnPrimaryUtc">
      <MemberSignature Language="C#" Value="public DateTime LastModifiedOnPrimaryUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastModifiedOnPrimaryUtc" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.KeyValueStoreItemMetadata.LastModifiedOnPrimaryUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastModifiedOnPrimaryUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastModifiedOnPrimaryUtc : DateTime" Usage="System.Fabric.KeyValueStoreItemMetadata.LastModifiedOnPrimaryUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            Ruft Uhrzeit (UTC) von der letzten Änderung der <see cref="T:System.Fabric.KeyValueStoreItem" /> Objekt vom primären Replikat des Diensts.
            </para>
        </summary>
        <value>
          <para>
            Ein <see cref="T:System.DateTime" /> , stellt der letzten Zeit der Änderung der <see cref="T:System.Fabric.KeyValueStoreItem" /> Objekt für das primäre Replikat des Diensts.
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModifiedUtc">
      <MemberSignature Language="C#" Value="public DateTime LastModifiedUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastModifiedUtc" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.KeyValueStoreItemMetadata.LastModifiedUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastModifiedUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastModifiedUtc : DateTime" Usage="System.Fabric.KeyValueStoreItemMetadata.LastModifiedUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft Uhrzeit (UTC) von der letzten Änderung der <see cref="T:System.Fabric.KeyValueStoreItem" /> Objekt.</para>
        </summary>
        <value>
          <para>Ein <see cref="T:System.DateTime" /> , stellt der letzten Zeit der Änderung der <see cref="T:System.Fabric.KeyValueStoreItem" /> Objekt.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SequenceNumber">
      <MemberSignature Language="C#" Value="public long SequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SequenceNumber" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.KeyValueStoreItemMetadata.SequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.SequenceNumber : int64" Usage="System.Fabric.KeyValueStoreItemMetadata.SequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Sequenznummer des der <see cref="T:System.Fabric.KeyValueStoreItem" /> Objekt.</para>
        </summary>
        <value>
          <para>Die Sequenznummer des der <see cref="T:System.Fabric.KeyValueStoreItem" /> Objekt als eine <see cref="T:System.Int64" />.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValueSizeInBytes">
      <MemberSignature Language="C#" Value="public int ValueSizeInBytes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ValueSizeInBytes" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.KeyValueStoreItemMetadata.ValueSizeInBytes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ValueSizeInBytes As Integer" />
      <MemberSignature Language="F#" Value="member this.ValueSizeInBytes : int" Usage="System.Fabric.KeyValueStoreItemMetadata.ValueSizeInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Größe in Bytes, der die Sequenznummer des der <see cref="T:System.Fabric.KeyValueStoreItem" /> Objekt.</para>
        </summary>
        <value>
          <para>Die Größe in Bytes, der die <see cref="T:System.Fabric.KeyValueStoreItem" /> Objekt als eine <see cref="T:System.Int32" />.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>