<Type Name="PartnerInfo" FullName="Microsoft.Azure.Management.Sql.Models.PartnerInfo">
  <TypeSignature Language="C#" Value="public class PartnerInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PartnerInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.PartnerInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class PartnerInfo" />
  <TypeSignature Language="F#" Value="type PartnerInfo = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d1344-101">Partner-Serverinformationen für die Failover-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="d1344-101">Partner server information for the failover group.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PartnerInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.PartnerInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d1344-102">Initialisiert eine neue Instanz der PartnerInfo-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d1344-102">Initializes a new instance of the PartnerInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PartnerInfo (string id, string location = null, string replicationRole = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string location, string replicationRole) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.PartnerInfo.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (id As String, Optional location As String = null, Optional replicationRole As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.PartnerInfo : string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.PartnerInfo" Usage="new Microsoft.Azure.Management.Sql.Models.PartnerInfo (id, location, replicationRole)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="replicationRole" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="d1344-103">Der Ressourcenbezeichner des Partnerservers.</span><span class="sxs-lookup"><span data-stu-id="d1344-103">Resource identifier of the partner server.</span></span></param>
        <param name="location"><span data-ttu-id="d1344-104">GeoLocation des Partnerservers.</span><span class="sxs-lookup"><span data-stu-id="d1344-104">Geo location of the partner server.</span></span></param>
        <param name="replicationRole"><span data-ttu-id="d1344-105">Replikationsrolle des Partnerservers.</span><span class="sxs-lookup"><span data-stu-id="d1344-105">Replication role of the partner server.</span></span> <span data-ttu-id="d1344-106">Folgende Werte sind möglich: 'Primary', 'Sekundären'</span><span class="sxs-lookup"><span data-stu-id="d1344-106">Possible values include: 'Primary', 'Secondary'</span></span></param>
        <summary>
            <span data-ttu-id="d1344-107">Initialisiert eine neue Instanz der PartnerInfo-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d1344-107">Initializes a new instance of the PartnerInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.PartnerInfo.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.PartnerInfo.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d1344-108">Ruft ab, oder legt Sie Ressourcenbezeichner des Partnerservers fest.</span><span class="sxs-lookup"><span data-stu-id="d1344-108">Gets or sets resource identifier of the partner server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.PartnerInfo.Location" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string" Usage="Microsoft.Azure.Management.Sql.Models.PartnerInfo.Location" />
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
            <span data-ttu-id="d1344-109">Ruft die geografischen Standort des Partnerservers ab.</span><span class="sxs-lookup"><span data-stu-id="d1344-109">Gets geo location of the partner server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicationRole">
      <MemberSignature Language="C#" Value="public string ReplicationRole { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplicationRole" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.PartnerInfo.ReplicationRole" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicationRole As String" />
      <MemberSignature Language="F#" Value="member this.ReplicationRole : string" Usage="Microsoft.Azure.Management.Sql.Models.PartnerInfo.ReplicationRole" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="replicationRole")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d1344-110">Ruft die replikationsrolle des Partnerservers ab.</span><span class="sxs-lookup"><span data-stu-id="d1344-110">Gets replication role of the partner server.</span></span> <span data-ttu-id="d1344-111">Folgende Werte sind möglich: 'Primary', 'Sekundären'</span><span class="sxs-lookup"><span data-stu-id="d1344-111">Possible values include: 'Primary', 'Secondary'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.PartnerInfo.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="partnerInfo.Validate " />
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
            <span data-ttu-id="d1344-112">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="d1344-112">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d1344-113">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="d1344-113">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>