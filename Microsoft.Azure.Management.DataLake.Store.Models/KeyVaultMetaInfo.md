<Type Name="KeyVaultMetaInfo" FullName="Microsoft.Azure.Management.DataLake.Store.Models.KeyVaultMetaInfo">
  <TypeSignature Language="C#" Value="public class KeyVaultMetaInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit KeyVaultMetaInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.Models.KeyVaultMetaInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class KeyVaultMetaInfo" />
  <TypeSignature Language="F#" Value="type KeyVaultMetaInfo = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Metadateninformationen, die durch die kontoverschlüsselung verwendet werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyVaultMetaInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.KeyVaultMetaInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der KeyVaultMetaInfo-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyVaultMetaInfo (string keyVaultResourceId, string encryptionKeyName, string encryptionKeyVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string keyVaultResourceId, string encryptionKeyName, string encryptionKeyVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.KeyVaultMetaInfo.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (keyVaultResourceId As String, encryptionKeyName As String, encryptionKeyVersion As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Store.Models.KeyVaultMetaInfo : string * string * string -&gt; Microsoft.Azure.Management.DataLake.Store.Models.KeyVaultMetaInfo" Usage="new Microsoft.Azure.Management.DataLake.Store.Models.KeyVaultMetaInfo (keyVaultResourceId, encryptionKeyName, encryptionKeyVersion)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="keyVaultResourceId" Type="System.String" />
        <Parameter Name="encryptionKeyName" Type="System.String" />
        <Parameter Name="encryptionKeyVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="keyVaultResourceId">Der Ressourcenbezeichner für den Benutzer verwaltet Key Vault, die zum Verschlüsseln verwendet wird.</param>
        <param name="encryptionKeyName">Der Name des Verschlüsselungsschlüssels für verwaltete Benutzer.</param>
        <param name="encryptionKeyVersion">Die Version des Verschlüsselungsschlüssels für verwaltete Benutzer.</param>
        <summary>
            Initialisiert eine neue Instanz der KeyVaultMetaInfo-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionKeyName">
      <MemberSignature Language="C#" Value="public string EncryptionKeyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EncryptionKeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.KeyVaultMetaInfo.EncryptionKeyName" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptionKeyName As String" />
      <MemberSignature Language="F#" Value="member this.EncryptionKeyName : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.Models.KeyVaultMetaInfo.EncryptionKeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="encryptionKeyName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen des verwalteten Verschlüsselungsschlüssels Benutzer fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionKeyVersion">
      <MemberSignature Language="C#" Value="public string EncryptionKeyVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EncryptionKeyVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.KeyVaultMetaInfo.EncryptionKeyVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptionKeyVersion As String" />
      <MemberSignature Language="F#" Value="member this.EncryptionKeyVersion : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.Models.KeyVaultMetaInfo.EncryptionKeyVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="encryptionKeyVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Version des Verschlüsselungsschlüssels für verwaltete Benutzer.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyVaultResourceId">
      <MemberSignature Language="C#" Value="public string KeyVaultResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyVaultResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.KeyVaultMetaInfo.KeyVaultResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyVaultResourceId As String" />
      <MemberSignature Language="F#" Value="member this.KeyVaultResourceId : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.Models.KeyVaultMetaInfo.KeyVaultResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keyVaultResourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt verwaltet den Ressourcenbezeichner für den Benutzer Key Vault, die zum Verschlüsseln verwendet wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.KeyVaultMetaInfo.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="keyVaultMetaInfo.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Überprüfen Sie das Objekt.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn die Validierung fehlschlägt
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>