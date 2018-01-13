<Type Name="AzureStorageCredentialsInfo" FullName="Microsoft.Azure.Management.BatchAI.Models.AzureStorageCredentialsInfo">
  <TypeSignature Language="C#" Value="public class AzureStorageCredentialsInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureStorageCredentialsInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.AzureStorageCredentialsInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureStorageCredentialsInfo" />
  <TypeSignature Language="F#" Value="type AzureStorageCredentialsInfo = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Anmeldeinformationen für den Zugriff auf Azure-Dateifreigabe.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureStorageCredentialsInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.AzureStorageCredentialsInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der AzureStorageCredentialsInfo-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureStorageCredentialsInfo (string accountKey = null, Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference accountKeySecretReference = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string accountKey, class Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference accountKeySecretReference) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.AzureStorageCredentialsInfo.#ctor(System.String,Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional accountKey As String = null, Optional accountKeySecretReference As KeyVaultSecretReference = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.AzureStorageCredentialsInfo : string * Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference -&gt; Microsoft.Azure.Management.BatchAI.Models.AzureStorageCredentialsInfo" Usage="new Microsoft.Azure.Management.BatchAI.Models.AzureStorageCredentialsInfo (accountKey, accountKeySecretReference)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="accountKey" Type="System.String" />
        <Parameter Name="accountKeySecretReference" Type="Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference" />
      </Parameters>
      <Docs>
        <param name="accountKey">Der speicherkontoschlüssel.</param>
        <param name="accountKeySecretReference">Gibt den Speicherort der speicherkontoschlüssel, die einen Key Vault geheimen Schlüssel ist.</param>
        <summary>
            Initialisiert eine neue Instanz der AzureStorageCredentialsInfo-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountKey">
      <MemberSignature Language="C#" Value="public string AccountKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccountKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.AzureStorageCredentialsInfo.AccountKey" />
      <MemberSignature Language="VB.NET" Value="Public Property AccountKey As String" />
      <MemberSignature Language="F#" Value="member this.AccountKey : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.AzureStorageCredentialsInfo.AccountKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="accountKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest-speicherkontoschlüssel.
            </summary>
        <value>To be added.</value>
        <remarks>
            AccountKey oder AccountKeySecretReference muss angegeben werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountKeySecretReference">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference AccountKeySecretReference { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference AccountKeySecretReference" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.AzureStorageCredentialsInfo.AccountKeySecretReference" />
      <MemberSignature Language="VB.NET" Value="Public Property AccountKeySecretReference As KeyVaultSecretReference" />
      <MemberSignature Language="F#" Value="member this.AccountKeySecretReference : Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.AzureStorageCredentialsInfo.AccountKeySecretReference" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="accountKeySecretReference")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt den Speicherort der speicherkontoschlüssel, also ein Schlüssel Vault Geheimnis, ruft ab oder legt ihn fest.
            </summary>
        <value>To be added.</value>
        <remarks>
            Benutzer können ihre geheime Schlüssel in Azure KeyVault speichern und übergibt ihn dann an den Batch AI-Dienst für die Integration von KeyVault. AccountKey oder AccountKeySecretReference muss angegeben werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.AzureStorageCredentialsInfo.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="azureStorageCredentialsInfo.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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