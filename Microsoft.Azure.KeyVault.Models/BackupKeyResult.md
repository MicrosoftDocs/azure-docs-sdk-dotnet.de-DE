<Type Name="BackupKeyResult" FullName="Microsoft.Azure.KeyVault.Models.BackupKeyResult">
  <TypeSignature Language="C#" Value="public class BackupKeyResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BackupKeyResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.BackupKeyResult" />
  <TypeSignature Language="VB.NET" Value="Public Class BackupKeyResult" />
  <TypeSignature Language="F#" Value="type BackupKeyResult = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0b4da-101">Backup Key Ergebnis, das die Blob-Sicherungsdatei enthält.</span><span class="sxs-lookup"><span data-stu-id="0b4da-101">The backup key result, containing the backup blob.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupKeyResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.BackupKeyResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0b4da-102">Initialisiert eine neue Instanz der BackupKeyResult-Klasse.</span><span class="sxs-lookup"><span data-stu-id="0b4da-102">Initializes a new instance of the BackupKeyResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupKeyResult (byte[] value = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(unsigned int8[] value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.BackupKeyResult.#ctor(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional value As Byte() = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.BackupKeyResult : byte[] -&gt; Microsoft.Azure.KeyVault.Models.BackupKeyResult" Usage="new Microsoft.Azure.KeyVault.Models.BackupKeyResult value" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="value" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="value"><span data-ttu-id="0b4da-103">Der Blob-Sicherungsdatei, die die gesicherten Schlüssel enthält.</span><span class="sxs-lookup"><span data-stu-id="0b4da-103">The backup blob containing the backed up key.</span></span></param>
        <summary>
            <span data-ttu-id="0b4da-104">Initialisiert eine neue Instanz der BackupKeyResult-Klasse.</span><span class="sxs-lookup"><span data-stu-id="0b4da-104">Initializes a new instance of the BackupKeyResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public byte[] Value { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.BackupKeyResult.Value" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Value As Byte()" />
      <MemberSignature Language="F#" Value="member this.Value : byte[]" Usage="Microsoft.Azure.KeyVault.Models.BackupKeyResult.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Rest.Serialization.Base64UrlJsonConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0b4da-105">Ruft die Blob-Sicherungsdatei mit dem gesicherten Schlüssel ab.</span><span class="sxs-lookup"><span data-stu-id="0b4da-105">Gets the backup blob containing the backed up key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>