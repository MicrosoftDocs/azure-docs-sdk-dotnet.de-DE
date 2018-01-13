<Type Name="Updates" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.Updates">
  <TypeSignature Language="C#" Value="public class Updates : Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Updates extends Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.Updates" />
  <TypeSignature Language="VB.NET" Value="Public Class Updates&#xA;Inherits BaseModel" />
  <TypeSignature Language="F#" Value="type Updates = class&#xA;    inherit BaseModel" />
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
            <span data-ttu-id="8d1a1-101">Das Profil Updates eines Geräts.</span><span class="sxs-lookup"><span data-stu-id="8d1a1-101">The updates profile of a device.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Updates ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.Updates.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8d1a1-102">Initialisiert eine neue Instanz der Klasse Updates an.</span><span class="sxs-lookup"><span data-stu-id="8d1a1-102">Initializes a new instance of the Updates class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Updates (string id = null, string name = null, string type = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind = null, Nullable&lt;bool&gt; regularUpdatesAvailable = null, Nullable&lt;bool&gt; maintenanceModeUpdatesAvailable = null, Nullable&lt;bool&gt; isUpdateInProgress = null, Nullable&lt;DateTime&gt; lastUpdatedTime = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind, valuetype System.Nullable`1&lt;bool&gt; regularUpdatesAvailable, valuetype System.Nullable`1&lt;bool&gt; maintenanceModeUpdatesAvailable, valuetype System.Nullable`1&lt;bool&gt; isUpdateInProgress, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastUpdatedTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.Updates.#ctor(System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.Kind},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional kind As Nullable(Of Kind) = null, Optional regularUpdatesAvailable As Nullable(Of Boolean) = null, Optional maintenanceModeUpdatesAvailable As Nullable(Of Boolean) = null, Optional isUpdateInProgress As Nullable(Of Boolean) = null, Optional lastUpdatedTime As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.Updates : string * string * string * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.Updates" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.Updates (id, name, type, kind, regularUpdatesAvailable, maintenanceModeUpdatesAvailable, isUpdateInProgress, lastUpdatedTime)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="kind" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt;" />
        <Parameter Name="regularUpdatesAvailable" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="maintenanceModeUpdatesAvailable" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="isUpdateInProgress" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="lastUpdatedTime" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="8d1a1-103">Die Pfad-ID, die das Objekt eindeutig identifiziert.</span><span class="sxs-lookup"><span data-stu-id="8d1a1-103">The path ID that uniquely identifies the object.</span></span></param>
        <param name="name"><span data-ttu-id="8d1a1-104">Der Name des Objekts.</span><span class="sxs-lookup"><span data-stu-id="8d1a1-104">The name of the object.</span></span></param>
        <param name="type"><span data-ttu-id="8d1a1-105">Der hierarchische Typ des Objekts.</span><span class="sxs-lookup"><span data-stu-id="8d1a1-105">The hierarchical type of the object.</span></span></param>
        <param name="kind"><span data-ttu-id="8d1a1-106">Die Art des Objekts.</span><span class="sxs-lookup"><span data-stu-id="8d1a1-106">The Kind of the object.</span></span> <span data-ttu-id="8d1a1-107">Derzeit wird nur Series8000 wird unterstützt.</span><span class="sxs-lookup"><span data-stu-id="8d1a1-107">Currently only Series8000 is supported.</span></span> <span data-ttu-id="8d1a1-108">Folgende Werte sind möglich: "Series8000"</span><span class="sxs-lookup"><span data-stu-id="8d1a1-108">Possible values include: 'Series8000'</span></span></param>
        <param name="regularUpdatesAvailable"><span data-ttu-id="8d1a1-109">Legen Sie auf 'true', wenn Sie regelmäßige Updates für das Gerät verfügbar sind.</span><span class="sxs-lookup"><span data-stu-id="8d1a1-109">Set to 'true' if regular updates are available for the device.</span></span></param>
        <param name="maintenanceModeUpdatesAvailable"><span data-ttu-id="8d1a1-110">Legen Sie auf 'true', wenn aktualisieren Sie den Wartungsmodus verfügbar.</span><span class="sxs-lookup"><span data-stu-id="8d1a1-110">Set to 'true' if maintenance mode update available.</span></span></param>
        <param name="isUpdateInProgress"><span data-ttu-id="8d1a1-111">Gibt an, ob ein Update ausgeführt, oder nicht wird.</span><span class="sxs-lookup"><span data-stu-id="8d1a1-111">Indicates whether an update is in progress or not.</span></span></param>
        <param name="lastUpdatedTime"><span data-ttu-id="8d1a1-112">Der Zeitpunkt, wenn das letzte Update abgeschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="8d1a1-112">The time when the last update was completed.</span></span></param>
        <summary>
            <span data-ttu-id="8d1a1-113">Initialisiert eine neue Instanz der Klasse Updates an.</span><span class="sxs-lookup"><span data-stu-id="8d1a1-113">Initializes a new instance of the Updates class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsUpdateInProgress">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsUpdateInProgress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsUpdateInProgress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Updates.IsUpdateInProgress" />
      <MemberSignature Language="VB.NET" Value="Public Property IsUpdateInProgress As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsUpdateInProgress : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Updates.IsUpdateInProgress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.isUpdateInProgress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8d1a1-114">Gibt an, ob ein Update ausgeführt wird, oder nicht, ruft ab oder legt ihn fest.</span><span class="sxs-lookup"><span data-stu-id="8d1a1-114">Gets or sets indicates whether an update is in progress or not.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastUpdatedTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastUpdatedTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastUpdatedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Updates.LastUpdatedTime" />
      <MemberSignature Language="VB.NET" Value="Public Property LastUpdatedTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastUpdatedTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Updates.LastUpdatedTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lastUpdatedTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8d1a1-115">Ruft ab oder legt die Zeit, wenn das letzte Update abgeschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="8d1a1-115">Gets or sets the time when the last update was completed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaintenanceModeUpdatesAvailable">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; MaintenanceModeUpdatesAvailable { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; MaintenanceModeUpdatesAvailable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Updates.MaintenanceModeUpdatesAvailable" />
      <MemberSignature Language="VB.NET" Value="Public Property MaintenanceModeUpdatesAvailable As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.MaintenanceModeUpdatesAvailable : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Updates.MaintenanceModeUpdatesAvailable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maintenanceModeUpdatesAvailable")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8d1a1-116">Ruft ab oder legt diese fest auf "true", wenn aktualisieren Sie den Wartungsmodus verfügbar.</span><span class="sxs-lookup"><span data-stu-id="8d1a1-116">Gets or sets set to 'true' if maintenance mode update available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegularUpdatesAvailable">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; RegularUpdatesAvailable { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; RegularUpdatesAvailable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Updates.RegularUpdatesAvailable" />
      <MemberSignature Language="VB.NET" Value="Public Property RegularUpdatesAvailable As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RegularUpdatesAvailable : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Updates.RegularUpdatesAvailable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.regularUpdatesAvailable")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8d1a1-117">Ruft ab oder legt auf "True" gesetzt, wenn reguläre Updates für das Gerät verfügbar sind.</span><span class="sxs-lookup"><span data-stu-id="8d1a1-117">Gets or sets set to 'true' if regular updates are available for the device.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>