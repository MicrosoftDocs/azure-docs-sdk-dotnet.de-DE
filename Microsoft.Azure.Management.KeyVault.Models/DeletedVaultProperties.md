<Type Name="DeletedVaultProperties" FullName="Microsoft.Azure.Management.KeyVault.Models.DeletedVaultProperties">
  <TypeSignature Language="C#" Value="public class DeletedVaultProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DeletedVaultProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.KeyVault.Models.DeletedVaultProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class DeletedVaultProperties" />
  <TypeSignature Language="F#" Value="type DeletedVaultProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="cd990-101">Eigenschaften des gelöschten Tresors.</span><span class="sxs-lookup"><span data-stu-id="cd990-101">Properties of the deleted vault.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeletedVaultProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Models.DeletedVaultProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="cd990-102">Initialisiert eine neue Instanz der DeletedVaultProperties-Klasse.</span><span class="sxs-lookup"><span data-stu-id="cd990-102">Initializes a new instance of the DeletedVaultProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeletedVaultProperties (string vaultId = null, string location = null, Nullable&lt;DateTime&gt; deletionDate = null, Nullable&lt;DateTime&gt; scheduledPurgeDate = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string vaultId, string location, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; deletionDate, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; scheduledPurgeDate, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Models.DeletedVaultProperties.#ctor(System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional vaultId As String = null, Optional location As String = null, Optional deletionDate As Nullable(Of DateTime) = null, Optional scheduledPurgeDate As Nullable(Of DateTime) = null, Optional tags As IDictionary(Of String, String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.KeyVault.Models.DeletedVaultProperties : string * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.KeyVault.Models.DeletedVaultProperties" Usage="new Microsoft.Azure.Management.KeyVault.Models.DeletedVaultProperties (vaultId, location, deletionDate, scheduledPurgeDate, tags)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="vaultId" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="deletionDate" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="scheduledPurgeDate" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="vaultId"><span data-ttu-id="cd990-103">Die Ressourcen-Id des ursprünglichen Tresors.</span><span class="sxs-lookup"><span data-stu-id="cd990-103">The resource id of the original vault.</span></span></param>
        <param name="location"><span data-ttu-id="cd990-104">Der Speicherort des ursprünglichen Tresors.</span><span class="sxs-lookup"><span data-stu-id="cd990-104">The location of the original vault.</span></span></param>
        <param name="deletionDate"><span data-ttu-id="cd990-105">Das gelöschte Datum.</span><span class="sxs-lookup"><span data-stu-id="cd990-105">The deleted date.</span></span></param>
        <param name="scheduledPurgeDate"><span data-ttu-id="cd990-106">Das Datum, geplante gelöscht.</span><span class="sxs-lookup"><span data-stu-id="cd990-106">The scheduled purged date.</span></span></param>
        <param name="tags"><span data-ttu-id="cd990-107">Die Tags des ursprünglichen Tresors.</span><span class="sxs-lookup"><span data-stu-id="cd990-107">Tags of the original vault.</span></span></param>
        <summary>
            <span data-ttu-id="cd990-108">Initialisiert eine neue Instanz der DeletedVaultProperties-Klasse.</span><span class="sxs-lookup"><span data-stu-id="cd990-108">Initializes a new instance of the DeletedVaultProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeletionDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; DeletionDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; DeletionDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Models.DeletedVaultProperties.DeletionDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeletionDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.DeletionDate : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.KeyVault.Models.DeletedVaultProperties.DeletionDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="deletionDate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cd990-109">Ruft die gelöschten Datum ab.</span><span class="sxs-lookup"><span data-stu-id="cd990-109">Gets the deleted date.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Models.DeletedVaultProperties.Location" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string" Usage="Microsoft.Azure.Management.KeyVault.Models.DeletedVaultProperties.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="location")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cd990-110">Ruft den Speicherort des ursprünglichen Tresors.</span><span class="sxs-lookup"><span data-stu-id="cd990-110">Gets the location of the original vault.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduledPurgeDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ScheduledPurgeDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ScheduledPurgeDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Models.DeletedVaultProperties.ScheduledPurgeDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ScheduledPurgeDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ScheduledPurgeDate : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.KeyVault.Models.DeletedVaultProperties.ScheduledPurgeDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="scheduledPurgeDate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cd990-111">Ruft das Datum des geplanten gelöscht.</span><span class="sxs-lookup"><span data-stu-id="cd990-111">Gets the scheduled purged date.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Models.DeletedVaultProperties.Tags" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.Azure.Management.KeyVault.Models.DeletedVaultProperties.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tags")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cd990-112">Ruft den ursprünglichen Vaults Tags ab.</span><span class="sxs-lookup"><span data-stu-id="cd990-112">Gets tags of the original vault.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VaultId">
      <MemberSignature Language="C#" Value="public string VaultId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VaultId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Models.DeletedVaultProperties.VaultId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VaultId As String" />
      <MemberSignature Language="F#" Value="member this.VaultId : string" Usage="Microsoft.Azure.Management.KeyVault.Models.DeletedVaultProperties.VaultId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="vaultId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cd990-113">Ruft die Ressourcen-Id des ursprünglichen Tresors ab.</span><span class="sxs-lookup"><span data-stu-id="cd990-113">Gets the resource id of the original vault.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>