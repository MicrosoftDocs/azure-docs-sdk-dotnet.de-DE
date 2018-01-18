<Type Name="BackupFilter" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter">
  <TypeSignature Language="C#" Value="public class BackupFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BackupFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class BackupFilter" />
  <TypeSignature Language="F#" Value="type BackupFilter = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7d133-101">Die OData-Filter für Sicherungen verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="7d133-101">The OData filters to be used for backups.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7d133-102">Initialisiert eine neue Instanz der BackupFilter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="7d133-102">Initializes a new instance of the BackupFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupFilter (string backupPolicyId = null, string volumeId = null, Nullable&lt;DateTime&gt; createdTime = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string backupPolicyId, string volumeId, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; createdTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter.#ctor(System.String,System.String,System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional backupPolicyId As String = null, Optional volumeId As String = null, Optional createdTime As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter : string * string * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter (backupPolicyId, volumeId, createdTime)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="backupPolicyId" Type="System.String" />
        <Parameter Name="volumeId" Type="System.String" />
        <Parameter Name="createdTime" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="backupPolicyId"><span data-ttu-id="7d133-103">Gibt die BackupPolicyId Sicherungen gefiltert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="7d133-103">Specifies the backupPolicyId of the backups to be filtered.</span></span> <span data-ttu-id="7d133-104">Für diese Eigenschaft wird nur "Gleichheitsoperator" unterstützt.</span><span class="sxs-lookup"><span data-stu-id="7d133-104">Only 'Equality' operator is supported for this property.</span></span></param>
        <param name="volumeId"><span data-ttu-id="7d133-105">Gibt die VolumeId Sicherungen gefiltert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="7d133-105">Specifies the volumeId of the backups to be filtered.</span></span> <span data-ttu-id="7d133-106">Für diese Eigenschaft wird nur "Gleichheitsoperator" unterstützt.</span><span class="sxs-lookup"><span data-stu-id="7d133-106">Only 'Equality' operator is supported for this property.</span></span></param>
        <param name="createdTime"><span data-ttu-id="7d133-107">Gibt den Zeitpunkt der Erstellung der Sicherungen gefiltert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="7d133-107">Specifies the creation time of the backups to be filtered.</span></span> <span data-ttu-id="7d133-108">Nur "größer als oder gleich" und "Kleiner als oder gleich" Operatoren für diese Eigenschaft unterstützt werden.</span><span class="sxs-lookup"><span data-stu-id="7d133-108">Only 'Greater Than or Equal To' and 'Lesser Than or Equal To' operators are supported for this property.</span></span></param>
        <summary>
            <span data-ttu-id="7d133-109">Initialisiert eine neue Instanz der BackupFilter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="7d133-109">Initializes a new instance of the BackupFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupPolicyId">
      <MemberSignature Language="C#" Value="public string BackupPolicyId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BackupPolicyId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter.BackupPolicyId" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupPolicyId As String" />
      <MemberSignature Language="F#" Value="member this.BackupPolicyId : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter.BackupPolicyId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="backupPolicyId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7d133-110">Ruft ab oder legt gibt die BackupPolicyId Sicherungen gefiltert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="7d133-110">Gets or sets specifies the backupPolicyId of the backups to be filtered.</span></span> <span data-ttu-id="7d133-111">Für diese Eigenschaft wird nur "Gleichheitsoperator" unterstützt.</span><span class="sxs-lookup"><span data-stu-id="7d133-111">Only 'Equality' operator is supported for this property.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreatedTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreatedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter.CreatedTime" />
      <MemberSignature Language="VB.NET" Value="Public Property CreatedTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreatedTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter.CreatedTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="createdTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7d133-112">Ruft ab oder legt gibt den Zeitpunkt der Erstellung der Sicherungen gefiltert werden.</span><span class="sxs-lookup"><span data-stu-id="7d133-112">Gets or sets specifies the creation time of the backups to be filtered.</span></span> <span data-ttu-id="7d133-113">Nur "größer als oder gleich" und "Kleiner als oder gleich" Operatoren für diese Eigenschaft unterstützt werden.</span><span class="sxs-lookup"><span data-stu-id="7d133-113">Only 'Greater Than or Equal To' and 'Lesser Than or Equal To' operators are supported for this property.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VolumeId">
      <MemberSignature Language="C#" Value="public string VolumeId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VolumeId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter.VolumeId" />
      <MemberSignature Language="VB.NET" Value="Public Property VolumeId As String" />
      <MemberSignature Language="F#" Value="member this.VolumeId : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter.VolumeId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="volumeId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7d133-114">Ruft ab oder legt gibt die VolumeId Sicherungen gefiltert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="7d133-114">Gets or sets specifies the volumeId of the backups to be filtered.</span></span>
            <span data-ttu-id="7d133-115">Für diese Eigenschaft wird nur "Gleichheitsoperator" unterstützt.</span><span class="sxs-lookup"><span data-stu-id="7d133-115">Only 'Equality' operator is supported for this property.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>