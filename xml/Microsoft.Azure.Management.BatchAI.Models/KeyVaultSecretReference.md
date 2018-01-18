<Type Name="KeyVaultSecretReference" FullName="Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference">
  <TypeSignature Language="C#" Value="public class KeyVaultSecretReference" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit KeyVaultSecretReference extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference" />
  <TypeSignature Language="VB.NET" Value="Public Class KeyVaultSecretReference" />
  <TypeSignature Language="F#" Value="type KeyVaultSecretReference = class" />
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
            <span data-ttu-id="fbd95-101">Beschreibt einen Verweis auf die Tresor geheimen Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="fbd95-101">Describes a reference to Key Vault Secret.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyVaultSecretReference ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="fbd95-102">Initialisiert eine neue Instanz der KeyVaultSecretReference-Klasse.</span><span class="sxs-lookup"><span data-stu-id="fbd95-102">Initializes a new instance of the KeyVaultSecretReference class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyVaultSecretReference (Microsoft.Azure.Management.BatchAI.Models.ResourceId sourceVault, string secretUrl);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.BatchAI.Models.ResourceId sourceVault, string secretUrl) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference.#ctor(Microsoft.Azure.Management.BatchAI.Models.ResourceId,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (sourceVault As ResourceId, secretUrl As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference : Microsoft.Azure.Management.BatchAI.Models.ResourceId * string -&gt; Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference" Usage="new Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference (sourceVault, secretUrl)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sourceVault" Type="Microsoft.Azure.Management.BatchAI.Models.ResourceId" />
        <Parameter Name="secretUrl" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sourceVault"><span data-ttu-id="fbd95-103">Vollqualifizierte Ressourcen-Id für den Schlüsseltresor.</span><span class="sxs-lookup"><span data-stu-id="fbd95-103">Fully qualified resource Id for the Key Vault.</span></span></param>
        <param name="secretUrl"><span data-ttu-id="fbd95-104">Die URL verweisen auf einen geheimen Schlüssel in einem Schlüsseltresor.</span><span class="sxs-lookup"><span data-stu-id="fbd95-104">The URL referencing a secret in a Key Vault.</span></span></param>
        <summary>
            <span data-ttu-id="fbd95-105">Initialisiert eine neue Instanz der KeyVaultSecretReference-Klasse.</span><span class="sxs-lookup"><span data-stu-id="fbd95-105">Initializes a new instance of the KeyVaultSecretReference class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecretUrl">
      <MemberSignature Language="C#" Value="public string SecretUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecretUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference.SecretUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property SecretUrl As String" />
      <MemberSignature Language="F#" Value="member this.SecretUrl : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference.SecretUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="fbd95-106">Ruft ab oder legt die URL verweisen auf einen geheimen Schlüssel in einem Schlüsseltresor.</span><span class="sxs-lookup"><span data-stu-id="fbd95-106">Gets or sets the URL referencing a secret in a Key Vault.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceVault">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.ResourceId SourceVault { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.ResourceId SourceVault" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference.SourceVault" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceVault As ResourceId" />
      <MemberSignature Language="F#" Value="member this.SourceVault : Microsoft.Azure.Management.BatchAI.Models.ResourceId with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference.SourceVault" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourceVault")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.ResourceId</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fbd95-107">Ruft ab oder legt den vollqualifizierten-Ressourcen-Id für den Schlüsseltresor.</span><span class="sxs-lookup"><span data-stu-id="fbd95-107">Gets or sets fully qualified resource Id for the Key Vault.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="keyVaultSecretReference.Validate " />
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
            <span data-ttu-id="fbd95-108">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="fbd95-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fbd95-109">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="fbd95-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>