<Type Name="EncryptionConfig" FullName="Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfig">
  <TypeSignature Language="C#" Value="public class EncryptionConfig" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EncryptionConfig extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfig" />
  <TypeSignature Language="VB.NET" Value="Public Class EncryptionConfig" />
  <TypeSignature Language="F#" Value="type EncryptionConfig = class" />
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
            Die Verschlüsselungskonfiguration für das Konto.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EncryptionConfig ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfig.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der EncryptionConfig-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EncryptionConfig (Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfigType type, Microsoft.Azure.Management.DataLake.Store.Models.KeyVaultMetaInfo keyVaultMetaInfo = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfigType type, class Microsoft.Azure.Management.DataLake.Store.Models.KeyVaultMetaInfo keyVaultMetaInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfig.#ctor(Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfigType,Microsoft.Azure.Management.DataLake.Store.Models.KeyVaultMetaInfo)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfig : Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfigType * Microsoft.Azure.Management.DataLake.Store.Models.KeyVaultMetaInfo -&gt; Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfig" Usage="new Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfig (type, keyVaultMetaInfo)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="type" Type="Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfigType" />
        <Parameter Name="keyVaultMetaInfo" Type="Microsoft.Azure.Management.DataLake.Store.Models.KeyVaultMetaInfo" />
      </Parameters>
      <Docs>
        <param name="type">Der Typ der Verschlüsselungskonfiguration verwendet wird.
            Aktuell sind die einzigen unterstützten Typen "UserManaged" und "ServiceManaged". Folgende Werte sind möglich: "UserManaged", "ServiceManaged"</param>
        <param name="keyVaultMetaInfo">Die Key Vault-Informationen für die Verbindung mit dem Benutzer verwaltet Verschlüsselungsschlüssel.</param>
        <summary>
            Initialisiert eine neue Instanz der EncryptionConfig-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyVaultMetaInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Store.Models.KeyVaultMetaInfo KeyVaultMetaInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Store.Models.KeyVaultMetaInfo KeyVaultMetaInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfig.KeyVaultMetaInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyVaultMetaInfo As KeyVaultMetaInfo" />
      <MemberSignature Language="F#" Value="member this.KeyVaultMetaInfo : Microsoft.Azure.Management.DataLake.Store.Models.KeyVaultMetaInfo with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfig.KeyVaultMetaInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keyVaultMetaInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.KeyVaultMetaInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Key Vault-Informationen für die Verbindung mit verwalteten Benutzer Verschlüsselungsschlüssel.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfigType Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfigType Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfig.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As EncryptionConfigType" />
      <MemberSignature Language="F#" Value="member this.Type : Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfigType with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfig.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfigType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Typ des verwendeten Verschlüsselungskonfiguration fest.
            Aktuell sind die einzigen unterstützten Typen "UserManaged" und "ServiceManaged". Folgende Werte sind möglich: "UserManaged", "ServiceManaged"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfig.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="encryptionConfig.Validate " />
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