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
            <span data-ttu-id="d522b-101">Metadateninformationen, die durch die kontoverschlüsselung verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="d522b-101">Metadata information used by account encryption.</span></span>
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
            <span data-ttu-id="d522b-102">Initialisiert eine neue Instanz der KeyVaultMetaInfo-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d522b-102">Initializes a new instance of the KeyVaultMetaInfo class.</span></span>
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
        <param name="keyVaultResourceId"><span data-ttu-id="d522b-103">Der Ressourcenbezeichner für den Benutzer verwaltet Key Vault, die zum Verschlüsseln verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="d522b-103">The resource identifier for the user managed Key Vault being used to encrypt.</span></span></param>
        <param name="encryptionKeyName"><span data-ttu-id="d522b-104">Der Name des Verschlüsselungsschlüssels für verwaltete Benutzer.</span><span class="sxs-lookup"><span data-stu-id="d522b-104">The name of the user managed encryption key.</span></span></param>
        <param name="encryptionKeyVersion"><span data-ttu-id="d522b-105">Die Version des Verschlüsselungsschlüssels für verwaltete Benutzer.</span><span class="sxs-lookup"><span data-stu-id="d522b-105">The version of the user managed encryption key.</span></span></param>
        <summary>
            <span data-ttu-id="d522b-106">Initialisiert eine neue Instanz der KeyVaultMetaInfo-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d522b-106">Initializes a new instance of the KeyVaultMetaInfo class.</span></span>
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
            <span data-ttu-id="d522b-107">Ruft ab oder legt den Namen des verwalteten Verschlüsselungsschlüssels Benutzer fest.</span><span class="sxs-lookup"><span data-stu-id="d522b-107">Gets or sets the name of the user managed encryption key.</span></span>
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
            <span data-ttu-id="d522b-108">Ruft ab oder legt die Version des Verschlüsselungsschlüssels für verwaltete Benutzer.</span><span class="sxs-lookup"><span data-stu-id="d522b-108">Gets or sets the version of the user managed encryption key.</span></span>
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
            <span data-ttu-id="d522b-109">Ruft ab oder legt verwaltet den Ressourcenbezeichner für den Benutzer Key Vault, die zum Verschlüsseln verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="d522b-109">Gets or sets the resource identifier for the user managed Key Vault being used to encrypt.</span></span>
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
            <span data-ttu-id="d522b-110">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="d522b-110">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d522b-111">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="d522b-111">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>