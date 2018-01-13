<Type Name="TimeSettings" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings">
  <TypeSignature Language="C#" Value="public class TimeSettings : Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TimeSettings extends Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class TimeSettings&#xA;Inherits BaseModel" />
  <TypeSignature Language="F#" Value="type TimeSettings = class&#xA;    inherit BaseModel" />
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
            <span data-ttu-id="352ef-101">Die Uhrzeiteinstellungen eines Geräts.</span><span class="sxs-lookup"><span data-stu-id="352ef-101">The time settings of a device.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TimeSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="352ef-102">Initialisiert eine neue Instanz der TimeSettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="352ef-102">Initializes a new instance of the TimeSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TimeSettings (string timeZone, string id = null, string name = null, string type = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind = null, string primaryTimeServer = null, System.Collections.Generic.IList&lt;string&gt; secondaryTimeServer = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string timeZone, string id, string name, string type, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind, string primaryTimeServer, class System.Collections.Generic.IList`1&lt;string&gt; secondaryTimeServer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings.#ctor(System.String,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.Kind},System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (timeZone As String, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional kind As Nullable(Of Kind) = null, Optional primaryTimeServer As String = null, Optional secondaryTimeServer As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings : string * string * string * string * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; * string * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings (timeZone, id, name, type, kind, primaryTimeServer, secondaryTimeServer)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="timeZone" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="kind" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt;" />
        <Parameter Name="primaryTimeServer" Type="System.String" />
        <Parameter Name="secondaryTimeServer" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="timeZone"><span data-ttu-id="352ef-103">Die Zeitzone des Geräts, z. B. "(UTC-06: 00) Central America"</span><span class="sxs-lookup"><span data-stu-id="352ef-103">The timezone of device, like '(UTC -06:00) Central America'</span></span></param>
        <param name="id"><span data-ttu-id="352ef-104">Die Pfad-ID, die das Objekt eindeutig identifiziert.</span><span class="sxs-lookup"><span data-stu-id="352ef-104">The path ID that uniquely identifies the object.</span></span></param>
        <param name="name"><span data-ttu-id="352ef-105">Der Name des Objekts.</span><span class="sxs-lookup"><span data-stu-id="352ef-105">The name of the object.</span></span></param>
        <param name="type"><span data-ttu-id="352ef-106">Der hierarchische Typ des Objekts.</span><span class="sxs-lookup"><span data-stu-id="352ef-106">The hierarchical type of the object.</span></span></param>
        <param name="kind"><span data-ttu-id="352ef-107">Die Art des Objekts.</span><span class="sxs-lookup"><span data-stu-id="352ef-107">The Kind of the object.</span></span> <span data-ttu-id="352ef-108">Derzeit wird nur Series8000 wird unterstützt.</span><span class="sxs-lookup"><span data-stu-id="352ef-108">Currently only Series8000 is supported.</span></span> <span data-ttu-id="352ef-109">Folgende Werte sind möglich: "Series8000"</span><span class="sxs-lookup"><span data-stu-id="352ef-109">Possible values include: 'Series8000'</span></span></param>
        <param name="primaryTimeServer"><span data-ttu-id="352ef-110">Der primäre Netzwerkzeitprotokoll (NTP)-Servername, z. B. "time.windows.com".</span><span class="sxs-lookup"><span data-stu-id="352ef-110">The primary Network Time Protocol (NTP) server name, like 'time.windows.com'.</span></span></param>
        <param name="secondaryTimeServer"><span data-ttu-id="352ef-111">Der sekundäre Netzwerkzeitprotokoll (NTP)-Servername, z. B. "time.contoso.com".</span><span class="sxs-lookup"><span data-stu-id="352ef-111">The secondary Network Time Protocol (NTP) server name, like 'time.contoso.com'.</span></span> <span data-ttu-id="352ef-112">Es ist optional.</span><span class="sxs-lookup"><span data-stu-id="352ef-112">It's optional.</span></span></param>
        <summary>
            <span data-ttu-id="352ef-113">Initialisiert eine neue Instanz der TimeSettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="352ef-113">Initializes a new instance of the TimeSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryTimeServer">
      <MemberSignature Language="C#" Value="public string PrimaryTimeServer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrimaryTimeServer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings.PrimaryTimeServer" />
      <MemberSignature Language="VB.NET" Value="Public Property PrimaryTimeServer As String" />
      <MemberSignature Language="F#" Value="member this.PrimaryTimeServer : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings.PrimaryTimeServer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.primaryTimeServer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="352ef-114">Ruft ab oder legt den Servernamen der primären Netzwerkzeitprotokoll (NTP), z. B. "time.windows.com" fest.</span><span class="sxs-lookup"><span data-stu-id="352ef-114">Gets or sets the primary Network Time Protocol (NTP) server name, like 'time.windows.com'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryTimeServer">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; SecondaryTimeServer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; SecondaryTimeServer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings.SecondaryTimeServer" />
      <MemberSignature Language="VB.NET" Value="Public Property SecondaryTimeServer As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.SecondaryTimeServer : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings.SecondaryTimeServer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.secondaryTimeServer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="352ef-115">Ruft ab oder legt den Servernamen der sekundären Netzwerkzeitprotokoll (NTP), z. B. "time.contoso.com" fest.</span><span class="sxs-lookup"><span data-stu-id="352ef-115">Gets or sets the secondary Network Time Protocol (NTP) server name, like 'time.contoso.com'.</span></span> <span data-ttu-id="352ef-116">Es ist optional.</span><span class="sxs-lookup"><span data-stu-id="352ef-116">It's optional.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeZone">
      <MemberSignature Language="C#" Value="public string TimeZone { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TimeZone" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings.TimeZone" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeZone As String" />
      <MemberSignature Language="F#" Value="member this.TimeZone : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings.TimeZone" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.timeZone")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="352ef-117">Ruft ab oder legt die Zeitzone des Geräts, z. B. "(UTC-06: 00) Central America"</span><span class="sxs-lookup"><span data-stu-id="352ef-117">Gets or sets the timezone of device, like '(UTC -06:00) Central America'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.TimeSettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="timeSettings.Validate " />
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
            <span data-ttu-id="352ef-118">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="352ef-118">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="352ef-119">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="352ef-119">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>