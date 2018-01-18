<Type Name="AppServiceCertificateResourceInner" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner">
  <TypeSignature Language="C#" Value="public class AppServiceCertificateResourceInner : Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AppServiceCertificateResourceInner extends Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner" />
  <TypeSignature Language="VB.NET" Value="Public Class AppServiceCertificateResourceInner&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type AppServiceCertificateResourceInner = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="d4cc9-101">Key Vault-Container ARM-Ressource für ein Zertifikat, das über Azure gekauft wurde.</span><span class="sxs-lookup"><span data-stu-id="d4cc9-101">Key Vault container ARM resource for a certificate that is purchased through Azure.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AppServiceCertificateResourceInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d4cc9-102">Initialisiert eine neue Instanz der AppServiceCertificateResourceInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d4cc9-102">Initializes a new instance of the AppServiceCertificateResourceInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AppServiceCertificateResourceInner (string location = null, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string keyVaultId = null, string keyVaultSecretName = null, Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.KeyVaultSecretStatus&gt; provisioningState = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string keyVaultId, string keyVaultSecretName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.KeyVaultSecretStatus&gt; provisioningState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.String,System.Nullable{Microsoft.Azure.Management.AppService.Fluent.Models.KeyVaultSecretStatus})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional location As String = null, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional keyVaultId As String = null, Optional keyVaultSecretName As String = null, Optional provisioningState As Nullable(Of KeyVaultSecretStatus) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * string * Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.KeyVaultSecretStatus&gt; -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner (location, id, name, type, tags, keyVaultId, keyVaultSecretName, provisioningState)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="keyVaultId" Type="System.String" />
        <Parameter Name="keyVaultSecretName" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.KeyVaultSecretStatus&gt;" />
      </Parameters>
      <Docs>
        <param name="location">To be added.</param>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="type">To be added.</param>
        <param name="tags">To be added.</param>
        <param name="keyVaultId"><span data-ttu-id="d4cc9-103">Key Vault-Ressourcen-ID</span><span class="sxs-lookup"><span data-stu-id="d4cc9-103">Key Vault resource Id.</span></span></param>
        <param name="keyVaultSecretName"><span data-ttu-id="d4cc9-104">Für den geheimen Key Vault-Name.</span><span class="sxs-lookup"><span data-stu-id="d4cc9-104">Key Vault secret name.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="d4cc9-105">Status des geheimen Schlüssels Key Vault.</span><span class="sxs-lookup"><span data-stu-id="d4cc9-105">Status of the Key Vault secret.</span></span>
            <span data-ttu-id="d4cc9-106">Folgende Werte sind möglich: "Initialisiert", "WaitingOnCertificateOrder", "Erfolgreich abgeschlossen", "CertificateOrderFailed", "OperationNotPermittedOnKeyVault", "AzureServiceUnauthorizedToAccessKeyVault", "KeyVaultDoesNotExist", " KeyVaultSecretDoesNotExist ", '" UnknownError "', 'ExternalPrivateKey', 'Unbekannt'</span><span class="sxs-lookup"><span data-stu-id="d4cc9-106">Possible values include: 'Initialized', 'WaitingOnCertificateOrder', 'Succeeded', 'CertificateOrderFailed', 'OperationNotPermittedOnKeyVault', 'AzureServiceUnauthorizedToAccessKeyVault', 'KeyVaultDoesNotExist', 'KeyVaultSecretDoesNotExist', 'UnknownError', 'ExternalPrivateKey', 'Unknown'</span></span></param>
        <summary>
            <span data-ttu-id="d4cc9-107">Initialisiert eine neue Instanz der AppServiceCertificateResourceInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d4cc9-107">Initializes a new instance of the AppServiceCertificateResourceInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyVaultId">
      <MemberSignature Language="C#" Value="public string KeyVaultId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyVaultId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner.KeyVaultId" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyVaultId As String" />
      <MemberSignature Language="F#" Value="member this.KeyVaultId : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner.KeyVaultId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.keyVaultId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d4cc9-108">Ruft ab oder legt ihn fest Key Vault-Ressourcen-ID</span><span class="sxs-lookup"><span data-stu-id="d4cc9-108">Gets or sets key Vault resource Id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyVaultSecretName">
      <MemberSignature Language="C#" Value="public string KeyVaultSecretName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyVaultSecretName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner.KeyVaultSecretName" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyVaultSecretName As String" />
      <MemberSignature Language="F#" Value="member this.KeyVaultSecretName : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner.KeyVaultSecretName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.keyVaultSecretName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d4cc9-109">Ruft ab, oder legt ihn fest Tresor geheimen Schlüsselnamen.</span><span class="sxs-lookup"><span data-stu-id="d4cc9-109">Gets or sets key Vault secret name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.KeyVaultSecretStatus&gt; ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.KeyVaultSecretStatus&gt; ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As Nullable(Of KeyVaultSecretStatus)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.KeyVaultSecretStatus&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.KeyVaultSecretStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d4cc9-110">Ruft den Status des Schlüsseltresors für den geheimen ab.</span><span class="sxs-lookup"><span data-stu-id="d4cc9-110">Gets status of the Key Vault secret.</span></span> <span data-ttu-id="d4cc9-111">Folgende Werte sind möglich: "Initialisiert", "WaitingOnCertificateOrder", "Erfolgreich abgeschlossen", "CertificateOrderFailed", "OperationNotPermittedOnKeyVault", "AzureServiceUnauthorizedToAccessKeyVault", "KeyVaultDoesNotExist", " KeyVaultSecretDoesNotExist ", '" UnknownError "', 'ExternalPrivateKey', 'Unbekannt'</span><span class="sxs-lookup"><span data-stu-id="d4cc9-111">Possible values include: 'Initialized', 'WaitingOnCertificateOrder', 'Succeeded', 'CertificateOrderFailed', 'OperationNotPermittedOnKeyVault', 'AzureServiceUnauthorizedToAccessKeyVault', 'KeyVaultDoesNotExist', 'KeyVaultSecretDoesNotExist', 'UnknownError', 'ExternalPrivateKey', 'Unknown'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>