<Type Name="AccessControlRecord" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord">
  <TypeSignature Language="C#" Value="public class AccessControlRecord : Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AccessControlRecord extends Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord" />
  <TypeSignature Language="VB.NET" Value="Public Class AccessControlRecord&#xA;Inherits BaseModel" />
  <TypeSignature Language="F#" Value="type AccessControlRecord = class&#xA;    inherit BaseModel" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="4c7f3-101">Der zugriffssteuerungsdatensatz.</span><span class="sxs-lookup"><span data-stu-id="4c7f3-101">The access control record.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AccessControlRecord ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4c7f3-102">Initialisiert eine neue Instanz der AccessControlRecord-Klasse.</span><span class="sxs-lookup"><span data-stu-id="4c7f3-102">Initializes a new instance of the AccessControlRecord class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AccessControlRecord (string initiatorName, string id = null, string name = null, string type = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind = null, Nullable&lt;int&gt; volumeCount = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string initiatorName, string id, string name, string type, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind, valuetype System.Nullable`1&lt;int32&gt; volumeCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord.#ctor(System.String,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.Kind},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (initiatorName As String, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional kind As Nullable(Of Kind) = null, Optional volumeCount As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord : string * string * string * string * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord (initiatorName, id, name, type, kind, volumeCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="initiatorName" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="kind" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt;" />
        <Parameter Name="volumeCount" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="initiatorName"><span data-ttu-id="4c7f3-103">Der iSCSI-Initiatorname (IQN).</span><span class="sxs-lookup"><span data-stu-id="4c7f3-103">The iSCSI initiator name (IQN).</span></span></param>
        <param name="id"><span data-ttu-id="4c7f3-104">Die Pfad-ID, die das Objekt eindeutig identifiziert.</span><span class="sxs-lookup"><span data-stu-id="4c7f3-104">The path ID that uniquely identifies the object.</span></span></param>
        <param name="name"><span data-ttu-id="4c7f3-105">Der Name des Objekts.</span><span class="sxs-lookup"><span data-stu-id="4c7f3-105">The name of the object.</span></span></param>
        <param name="type"><span data-ttu-id="4c7f3-106">Der hierarchische Typ des Objekts.</span><span class="sxs-lookup"><span data-stu-id="4c7f3-106">The hierarchical type of the object.</span></span></param>
        <param name="kind"><span data-ttu-id="4c7f3-107">Die Art des Objekts.</span><span class="sxs-lookup"><span data-stu-id="4c7f3-107">The Kind of the object.</span></span> <span data-ttu-id="4c7f3-108">Derzeit wird nur Series8000 wird unterstützt.</span><span class="sxs-lookup"><span data-stu-id="4c7f3-108">Currently only Series8000 is supported.</span></span> <span data-ttu-id="4c7f3-109">Folgende Werte sind möglich: "Series8000"</span><span class="sxs-lookup"><span data-stu-id="4c7f3-109">Possible values include: 'Series8000'</span></span></param>
        <param name="volumeCount"><span data-ttu-id="4c7f3-110">Die Anzahl der Volumes, Access Control Record verwenden.</span><span class="sxs-lookup"><span data-stu-id="4c7f3-110">The number of volumes using the access control record.</span></span></param>
        <summary>
            <span data-ttu-id="4c7f3-111">Initialisiert eine neue Instanz der AccessControlRecord-Klasse.</span><span class="sxs-lookup"><span data-stu-id="4c7f3-111">Initializes a new instance of the AccessControlRecord class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitiatorName">
      <MemberSignature Language="C#" Value="public string InitiatorName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InitiatorName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord.InitiatorName" />
      <MemberSignature Language="VB.NET" Value="Public Property InitiatorName As String" />
      <MemberSignature Language="F#" Value="member this.InitiatorName : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord.InitiatorName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.initiatorName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4c7f3-112">Ruft ab oder legt den iSCSI-Initiatorname (IQN).</span><span class="sxs-lookup"><span data-stu-id="4c7f3-112">Gets or sets the iSCSI initiator name (IQN).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="accessControlRecord.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4c7f3-113">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="4c7f3-113">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4c7f3-114">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="4c7f3-114">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VolumeCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; VolumeCount { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; VolumeCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord.VolumeCount" />
      <MemberSignature Language="VB.NET" Value="Public Property VolumeCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.VolumeCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord.VolumeCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.volumeCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4c7f3-115">Ruft die Anzahl der Volumes, Access Control Record verwenden.</span><span class="sxs-lookup"><span data-stu-id="4c7f3-115">Gets the number of volumes using the access control record.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>