<Type Name="PacketCaptureStorageLocation" FullName="Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureStorageLocation">
  <TypeSignature Language="C#" Value="public class PacketCaptureStorageLocation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PacketCaptureStorageLocation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureStorageLocation" />
  <TypeSignature Language="VB.NET" Value="Public Class PacketCaptureStorageLocation" />
  <TypeSignature Language="F#" Value="type PacketCaptureStorageLocation = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Beschreibt den Speicherort für eine sammlungssitzung Paket an.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PacketCaptureStorageLocation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureStorageLocation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der PacketCaptureStorageLocation-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PacketCaptureStorageLocation (string storageId = null, string storagePath = null, string filePath = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string storageId, string storagePath, string filePath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureStorageLocation.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional storageId As String = null, Optional storagePath As String = null, Optional filePath As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureStorageLocation : string * string * string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureStorageLocation" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureStorageLocation (storageId, storagePath, filePath)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageId" Type="System.String" />
        <Parameter Name="storagePath" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="storageId">Die ID des Speicherkontos, speichern Sie das Paket erfassen Sitzung. Erforderlich, wenn keine lokalen Pfad bereitgestellt wird.</param>
        <param name="storagePath">Der URI für den Speicherpfad der paketerfassung zu speichern. Muss ein wohlgeformter URI den Speicherort zum Speichern der paketerfassung beschreiben.</param>
        <param name="filePath">Einen gültigen lokalen Pfad auf dem Ziel virtuellen Computer. Muss den Namen der Capture-Datei enthalten (* CAP). Für den virtuellen Linux-Computer müssen mit /var/captures beginnen. Erforderlich, wenn keine Speicher-ID bereitgestellt, die andernfalls optional wird.</param>
        <summary>
            Initialisiert eine neue Instanz der PacketCaptureStorageLocation-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FilePath">
      <MemberSignature Language="C#" Value="public string FilePath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FilePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureStorageLocation.FilePath" />
      <MemberSignature Language="VB.NET" Value="Public Property FilePath As String" />
      <MemberSignature Language="F#" Value="member this.FilePath : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureStorageLocation.FilePath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="filePath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen gültigen lokalen Pfad auf dem Ziel virtuellen Computer. Muss den Namen der Capture-Datei enthalten (* CAP). Für den virtuellen Linux-Computer müssen mit /var/captures beginnen. Erforderlich, wenn keine Speicher-ID bereitgestellt, die andernfalls optional wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageId">
      <MemberSignature Language="C#" Value="public string StorageId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureStorageLocation.StorageId" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageId As String" />
      <MemberSignature Language="F#" Value="member this.StorageId : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureStorageLocation.StorageId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die ID des Speicherkontos zum Speichern der erfassungssitzung Paket fest. Erforderlich, wenn keine lokalen Pfad bereitgestellt wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoragePath">
      <MemberSignature Language="C#" Value="public string StoragePath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StoragePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureStorageLocation.StoragePath" />
      <MemberSignature Language="VB.NET" Value="Public Property StoragePath As String" />
      <MemberSignature Language="F#" Value="member this.StoragePath : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureStorageLocation.StoragePath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storagePath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder festlegen die URI der Speicherpfad, die paketerfassung zu speichern. Muss ein wohlgeformter URI den Speicherort zum Speichern der paketerfassung beschreiben.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>