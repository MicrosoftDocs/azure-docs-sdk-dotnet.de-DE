<Type Name="BandwidthSetting" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting">
  <TypeSignature Language="C#" Value="public class BandwidthSetting : Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BandwidthSetting extends Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting" />
  <TypeSignature Language="VB.NET" Value="Public Class BandwidthSetting&#xA;Inherits BaseModel" />
  <TypeSignature Language="F#" Value="type BandwidthSetting = class&#xA;    inherit BaseModel" />
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
            <span data-ttu-id="b7830-101">Die Einstellung für die Bandbreite.</span><span class="sxs-lookup"><span data-stu-id="b7830-101">The bandwidth setting.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BandwidthSetting ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b7830-102">Initialisiert eine neue Instanz der BandwidthSetting-Klasse.</span><span class="sxs-lookup"><span data-stu-id="b7830-102">Initializes a new instance of the BandwidthSetting class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BandwidthSetting (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSchedule&gt; schedules, string id = null, string name = null, string type = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind = null, Nullable&lt;int&gt; volumeCount = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSchedule&gt; schedules, string id, string name, string type, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind, valuetype System.Nullable`1&lt;int32&gt; volumeCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSchedule},System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.Kind},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (schedules As IList(Of BandwidthSchedule), Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional kind As Nullable(Of Kind) = null, Optional volumeCount As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSchedule&gt; * string * string * string * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting (schedules, id, name, type, kind, volumeCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="schedules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSchedule&gt;" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="kind" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt;" />
        <Parameter Name="volumeCount" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="schedules"><span data-ttu-id="b7830-103">Die Zeitpläne.</span><span class="sxs-lookup"><span data-stu-id="b7830-103">The schedules.</span></span></param>
        <param name="id"><span data-ttu-id="b7830-104">Die Pfad-ID, die das Objekt eindeutig identifiziert.</span><span class="sxs-lookup"><span data-stu-id="b7830-104">The path ID that uniquely identifies the object.</span></span></param>
        <param name="name"><span data-ttu-id="b7830-105">Der Name des Objekts.</span><span class="sxs-lookup"><span data-stu-id="b7830-105">The name of the object.</span></span></param>
        <param name="type"><span data-ttu-id="b7830-106">Der hierarchische Typ des Objekts.</span><span class="sxs-lookup"><span data-stu-id="b7830-106">The hierarchical type of the object.</span></span></param>
        <param name="kind"><span data-ttu-id="b7830-107">Die Art des Objekts.</span><span class="sxs-lookup"><span data-stu-id="b7830-107">The Kind of the object.</span></span> <span data-ttu-id="b7830-108">Derzeit wird nur Series8000 wird unterstützt.</span><span class="sxs-lookup"><span data-stu-id="b7830-108">Currently only Series8000 is supported.</span></span> <span data-ttu-id="b7830-109">Folgende Werte sind möglich: "Series8000"</span><span class="sxs-lookup"><span data-stu-id="b7830-109">Possible values include: 'Series8000'</span></span></param>
        <param name="volumeCount"><span data-ttu-id="b7830-110">Die Anzahl der Volumes, die die Einstellung für die Bandbreite verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="b7830-110">The number of volumes that uses the bandwidth setting.</span></span></param>
        <summary>
            <span data-ttu-id="b7830-111">Initialisiert eine neue Instanz der BandwidthSetting-Klasse.</span><span class="sxs-lookup"><span data-stu-id="b7830-111">Initializes a new instance of the BandwidthSetting class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Schedules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSchedule&gt; Schedules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSchedule&gt; Schedules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting.Schedules" />
      <MemberSignature Language="VB.NET" Value="Public Property Schedules As IList(Of BandwidthSchedule)" />
      <MemberSignature Language="F#" Value="member this.Schedules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSchedule&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting.Schedules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.schedules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSchedule&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b7830-112">Ruft ab oder legt die Zeitpläne.</span><span class="sxs-lookup"><span data-stu-id="b7830-112">Gets or sets the schedules.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="bandwidthSetting.Validate " />
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
            <span data-ttu-id="b7830-113">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="b7830-113">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b7830-114">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="b7830-114">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VolumeCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; VolumeCount { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; VolumeCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting.VolumeCount" />
      <MemberSignature Language="VB.NET" Value="Public Property VolumeCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.VolumeCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSetting.VolumeCount" />
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
            <span data-ttu-id="b7830-115">Ruft die Anzahl der Volumes, die die Einstellung für die Bandbreite verwendet.</span><span class="sxs-lookup"><span data-stu-id="b7830-115">Gets the number of volumes that uses the bandwidth setting.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>