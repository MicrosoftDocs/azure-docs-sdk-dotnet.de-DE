<Type Name="KeyVaultSecretReference" FullName="Microsoft.Azure.Management.Compute.Models.KeyVaultSecretReference">
  <TypeSignature Language="C#" Value="public class KeyVaultSecretReference" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit KeyVaultSecretReference extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.KeyVaultSecretReference" />
  <TypeSignature Language="VB.NET" Value="Public Class KeyVaultSecretReference" />
  <TypeSignature Language="F#" Value="type KeyVaultSecretReference = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="cff5a-101">Beschreibt einen Verweis für geheimen Schlüssel, Key Vault</span><span class="sxs-lookup"><span data-stu-id="cff5a-101">Describes a reference to Key Vault Secret</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyVaultSecretReference ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.KeyVaultSecretReference.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="cff5a-102">Initialisiert eine neue Instanz der KeyVaultSecretReference-Klasse.</span><span class="sxs-lookup"><span data-stu-id="cff5a-102">Initializes a new instance of the KeyVaultSecretReference class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyVaultSecretReference (string secretUrl, Microsoft.Azure.Management.Compute.Models.SubResource sourceVault);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string secretUrl, class Microsoft.Azure.Management.Compute.Models.SubResource sourceVault) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.KeyVaultSecretReference.#ctor(System.String,Microsoft.Azure.Management.Compute.Models.SubResource)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (secretUrl As String, sourceVault As SubResource)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.KeyVaultSecretReference : string * Microsoft.Azure.Management.Compute.Models.SubResource -&gt; Microsoft.Azure.Management.Compute.Models.KeyVaultSecretReference" Usage="new Microsoft.Azure.Management.Compute.Models.KeyVaultSecretReference (secretUrl, sourceVault)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="secretUrl" Type="System.String" />
        <Parameter Name="sourceVault" Type="Microsoft.Azure.Management.Compute.Models.SubResource" />
      </Parameters>
      <Docs>
        <param name="secretUrl"><span data-ttu-id="cff5a-103">Die URL verweisen auf einen geheimen Schlüssel in einem Schlüsseltresor.</span><span class="sxs-lookup"><span data-stu-id="cff5a-103">The URL referencing a secret in a Key Vault.</span></span></param>
        <param name="sourceVault"><span data-ttu-id="cff5a-104">Die relative URL des Tresors Schlüssel, den geheimen Schlüssel enthält.</span><span class="sxs-lookup"><span data-stu-id="cff5a-104">The relative URL of the Key Vault containing the secret.</span></span></param>
        <summary>
            <span data-ttu-id="cff5a-105">Initialisiert eine neue Instanz der KeyVaultSecretReference-Klasse.</span><span class="sxs-lookup"><span data-stu-id="cff5a-105">Initializes a new instance of the KeyVaultSecretReference class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecretUrl">
      <MemberSignature Language="C#" Value="public string SecretUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecretUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.KeyVaultSecretReference.SecretUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property SecretUrl As String" />
      <MemberSignature Language="F#" Value="member this.SecretUrl : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.KeyVaultSecretReference.SecretUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="secretUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cff5a-106">Ruft ab oder legt die URL verweisen auf einen geheimen Schlüssel in einem Schlüsseltresor.</span><span class="sxs-lookup"><span data-stu-id="cff5a-106">Gets or sets the URL referencing a secret in a Key Vault.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceVault">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.SubResource SourceVault { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.SubResource SourceVault" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.KeyVaultSecretReference.SourceVault" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceVault As SubResource" />
      <MemberSignature Language="F#" Value="member this.SourceVault : Microsoft.Azure.Management.Compute.Models.SubResource with get, set" Usage="Microsoft.Azure.Management.Compute.Models.KeyVaultSecretReference.SourceVault" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourceVault")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cff5a-107">Ruft ab oder legt die relative URL des Tresors Schlüssel, den geheimen Schlüssel enthält.</span><span class="sxs-lookup"><span data-stu-id="cff5a-107">Gets or sets the relative URL of the Key Vault containing the secret.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.KeyVaultSecretReference.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="keyVaultSecretReference.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="cff5a-108">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="cff5a-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="cff5a-109">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="cff5a-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>