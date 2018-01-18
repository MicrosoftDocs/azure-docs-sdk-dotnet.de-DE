<Type Name="BackupLongTermRetentionVault" FullName="Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault">
  <TypeSignature Language="C#" Value="public class BackupLongTermRetentionVault : Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BackupLongTermRetentionVault extends Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault" />
  <TypeSignature Language="VB.NET" Value="Public Class BackupLongTermRetentionVault&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type BackupLongTermRetentionVault = class&#xA;    inherit ProxyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Sql.Models.ProxyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="61a49-101">Eine Sicherung langfristige Aufbewahrung Tresor</span><span class="sxs-lookup"><span data-stu-id="61a49-101">A backup long term retention vault</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupLongTermRetentionVault ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="61a49-102">Initialisiert eine neue Instanz der BackupLongTermRetentionVault-Klasse.</span><span class="sxs-lookup"><span data-stu-id="61a49-102">Initializes a new instance of the BackupLongTermRetentionVault class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupLongTermRetentionVault (string recoveryServicesVaultResourceId, string id = null, string name = null, string type = null, string location = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string recoveryServicesVaultResourceId, string id, string name, string type, string location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault.#ctor(System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (recoveryServicesVaultResourceId As String, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional location As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault : string * string * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault" Usage="new Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault (recoveryServicesVaultResourceId, id, name, type, location)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="recoveryServicesVaultResourceId" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="recoveryServicesVaultResourceId"><span data-ttu-id="61a49-103">Die Azure Recovery Services-Tresor-Ressourcen-id</span><span class="sxs-lookup"><span data-stu-id="61a49-103">The azure recovery services vault resource id</span></span></param>
        <param name="id"><span data-ttu-id="61a49-104">Ressourcen-ID</span><span class="sxs-lookup"><span data-stu-id="61a49-104">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="61a49-105">Name der Ressource.</span><span class="sxs-lookup"><span data-stu-id="61a49-105">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="61a49-106">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="61a49-106">Resource type.</span></span></param>
        <param name="location"><span data-ttu-id="61a49-107">Der geografische Standort, in dem die Ressource aktiv ist</span><span class="sxs-lookup"><span data-stu-id="61a49-107">The geo-location where the resource lives</span></span></param>
        <summary>
            <span data-ttu-id="61a49-108">Initialisiert eine neue Instanz der BackupLongTermRetentionVault-Klasse.</span><span class="sxs-lookup"><span data-stu-id="61a49-108">Initializes a new instance of the BackupLongTermRetentionVault class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault.Location" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string" Usage="Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="61a49-109">Ruft den geografischen Standort aktiv ist, in dem die Ressource</span><span class="sxs-lookup"><span data-stu-id="61a49-109">Gets the geo-location where the resource lives</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoveryServicesVaultResourceId">
      <MemberSignature Language="C#" Value="public string RecoveryServicesVaultResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RecoveryServicesVaultResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault.RecoveryServicesVaultResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property RecoveryServicesVaultResourceId As String" />
      <MemberSignature Language="F#" Value="member this.RecoveryServicesVaultResourceId : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault.RecoveryServicesVaultResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.recoveryServicesVaultResourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="61a49-110">Ruft ab oder legt den Azure Recovery Services-Tresor-Ressourcen-id</span><span class="sxs-lookup"><span data-stu-id="61a49-110">Gets or sets the azure recovery services vault resource id</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="backupLongTermRetentionVault.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="61a49-111">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="61a49-111">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="61a49-112">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="61a49-112">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>