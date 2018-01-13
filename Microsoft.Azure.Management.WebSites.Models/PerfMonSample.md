<Type Name="PerfMonSample" FullName="Microsoft.Azure.Management.WebSites.Models.PerfMonSample">
  <TypeSignature Language="C#" Value="public class PerfMonSample" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PerfMonSample extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.PerfMonSample" />
  <TypeSignature Language="VB.NET" Value="Public Class PerfMonSample" />
  <TypeSignature Language="F#" Value="type PerfMonSample = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a296b-101">Performance Monitor-Beispiel in einem Satz.</span><span class="sxs-lookup"><span data-stu-id="a296b-101">Performance monitor sample in a set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PerfMonSample ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.PerfMonSample.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a296b-102">Initialisiert eine neue Instanz der PerfMonSample-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a296b-102">Initializes a new instance of the PerfMonSample class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PerfMonSample (Nullable&lt;DateTime&gt; time = null, string instanceName = null, Nullable&lt;double&gt; value = null, Nullable&lt;int&gt; coreCount = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; time, string instanceName, valuetype System.Nullable`1&lt;float64&gt; value, valuetype System.Nullable`1&lt;int32&gt; coreCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.PerfMonSample.#ctor(System.Nullable{System.DateTime},System.String,System.Nullable{System.Double},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional time As Nullable(Of DateTime) = null, Optional instanceName As String = null, Optional value As Nullable(Of Double) = null, Optional coreCount As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.PerfMonSample : Nullable&lt;DateTime&gt; * string * Nullable&lt;double&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.PerfMonSample" Usage="new Microsoft.Azure.Management.WebSites.Models.PerfMonSample (time, instanceName, value, coreCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="time" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="instanceName" Type="System.String" />
        <Parameter Name="value" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="coreCount" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="time"><span data-ttu-id="a296b-103">Zeitpunkt für den Leistungsindikator gemessen wurde.</span><span class="sxs-lookup"><span data-stu-id="a296b-103">Point in time for which counter was measured.</span></span></param>
        <param name="instanceName"><span data-ttu-id="a296b-104">Der Name des Servers, auf dem die Messung vorgenommen wird.</span><span class="sxs-lookup"><span data-stu-id="a296b-104">Name of the server on which the measurement is made.</span></span></param>
        <param name="value"><span data-ttu-id="a296b-105">Der Wert des Leistungsindikators zu einem bestimmten Zeitpunkt.</span><span class="sxs-lookup"><span data-stu-id="a296b-105">Value of counter at a certain time.</span></span></param>
        <param name="coreCount"><span data-ttu-id="a296b-106">Anzahl von Kernen des Arbeitsthreads.</span><span class="sxs-lookup"><span data-stu-id="a296b-106">Core Count of worker.</span></span> <span data-ttu-id="a296b-107">Nicht für ein Data-Element</span><span class="sxs-lookup"><span data-stu-id="a296b-107">Not a data member</span></span></param>
        <summary>
            <span data-ttu-id="a296b-108">Initialisiert eine neue Instanz der PerfMonSample-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a296b-108">Initializes a new instance of the PerfMonSample class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CoreCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; CoreCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; CoreCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.PerfMonSample.CoreCount" />
      <MemberSignature Language="VB.NET" Value="Public Property CoreCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.CoreCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.PerfMonSample.CoreCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="coreCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a296b-109">Ruft ab, oder legt ihn fest Core Anzahl von Arbeitsthreads.</span><span class="sxs-lookup"><span data-stu-id="a296b-109">Gets or sets core Count of worker.</span></span> <span data-ttu-id="a296b-110">Nicht für ein Data-Element</span><span class="sxs-lookup"><span data-stu-id="a296b-110">Not a data member</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstanceName">
      <MemberSignature Language="C#" Value="public string InstanceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InstanceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.PerfMonSample.InstanceName" />
      <MemberSignature Language="VB.NET" Value="Public Property InstanceName As String" />
      <MemberSignature Language="F#" Value="member this.InstanceName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.PerfMonSample.InstanceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="instanceName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a296b-111">Ruft ab, oder legt ihn fest Name des Servers, auf dem die Messung vorgenommen wird.</span><span class="sxs-lookup"><span data-stu-id="a296b-111">Gets or sets name of the server on which the measurement is made.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Time">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; Time { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; Time" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.PerfMonSample.Time" />
      <MemberSignature Language="VB.NET" Value="Public Property Time As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.Time : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.PerfMonSample.Time" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="time")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a296b-112">Ruft ab oder legt fest, zeigen Sie für den Leistungsindikator gemessen wurde.</span><span class="sxs-lookup"><span data-stu-id="a296b-112">Gets or sets point in time for which counter was measured.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; Value { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.PerfMonSample.Value" />
      <MemberSignature Language="VB.NET" Value="Public Property Value As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.Value : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.PerfMonSample.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a296b-113">Ruft ab oder legt der Wert des Leistungsindikators zu einem bestimmten Zeitpunkt.</span><span class="sxs-lookup"><span data-stu-id="a296b-113">Gets or sets value of counter at a certain time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>