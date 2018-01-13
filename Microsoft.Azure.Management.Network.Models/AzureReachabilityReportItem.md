<Type Name="AzureReachabilityReportItem" FullName="Microsoft.Azure.Management.Network.Models.AzureReachabilityReportItem">
  <TypeSignature Language="C#" Value="public class AzureReachabilityReportItem" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureReachabilityReportItem extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.AzureReachabilityReportItem" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureReachabilityReportItem" />
  <TypeSignature Language="F#" Value="type AzureReachabilityReportItem = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c1dd7-101">Azure Erreichbarkeit Berichtdetails für einen bestimmten Anbieter-Speicherort.</span><span class="sxs-lookup"><span data-stu-id="c1dd7-101">Azure reachability report details for a given provider location.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureReachabilityReportItem ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.AzureReachabilityReportItem.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c1dd7-102">Initialisiert eine neue Instanz der AzureReachabilityReportItem-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c1dd7-102">Initializes a new instance of the AzureReachabilityReportItem class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureReachabilityReportItem (string provider = null, string azureLocation = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLatencyInfo&gt; latencies = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string provider, string azureLocation, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLatencyInfo&gt; latencies) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.AzureReachabilityReportItem.#ctor(System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLatencyInfo})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional provider As String = null, Optional azureLocation As String = null, Optional latencies As IList(Of AzureReachabilityReportLatencyInfo) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.AzureReachabilityReportItem : string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLatencyInfo&gt; -&gt; Microsoft.Azure.Management.Network.Models.AzureReachabilityReportItem" Usage="new Microsoft.Azure.Management.Network.Models.AzureReachabilityReportItem (provider, azureLocation, latencies)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="provider" Type="System.String" />
        <Parameter Name="azureLocation" Type="System.String" />
        <Parameter Name="latencies" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLatencyInfo&gt;" />
      </Parameters>
      <Docs>
        <param name="provider"><span data-ttu-id="c1dd7-103">Der Internet-Dienstanbieter.</span><span class="sxs-lookup"><span data-stu-id="c1dd7-103">The Internet service provider.</span></span></param>
        <param name="azureLocation"><span data-ttu-id="c1dd7-104">Die Azure-Region.</span><span class="sxs-lookup"><span data-stu-id="c1dd7-104">The Azure region.</span></span></param>
        <param name="latencies"><span data-ttu-id="c1dd7-105">Liste der Latenz Details für jede Zeitreihe.</span><span class="sxs-lookup"><span data-stu-id="c1dd7-105">List of latency details for each of the time series.</span></span></param>
        <summary>
            <span data-ttu-id="c1dd7-106">Initialisiert eine neue Instanz der AzureReachabilityReportItem-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c1dd7-106">Initializes a new instance of the AzureReachabilityReportItem class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureLocation">
      <MemberSignature Language="C#" Value="public string AzureLocation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AzureLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.AzureReachabilityReportItem.AzureLocation" />
      <MemberSignature Language="VB.NET" Value="Public Property AzureLocation As String" />
      <MemberSignature Language="F#" Value="member this.AzureLocation : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.AzureReachabilityReportItem.AzureLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="azureLocation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c1dd7-107">Ruft ab oder legt die Azure-Region.</span><span class="sxs-lookup"><span data-stu-id="c1dd7-107">Gets or sets the Azure region.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Latencies">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLatencyInfo&gt; Latencies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLatencyInfo&gt; Latencies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.AzureReachabilityReportItem.Latencies" />
      <MemberSignature Language="VB.NET" Value="Public Property Latencies As IList(Of AzureReachabilityReportLatencyInfo)" />
      <MemberSignature Language="F#" Value="member this.Latencies : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLatencyInfo&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.AzureReachabilityReportItem.Latencies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="latencies")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLatencyInfo&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c1dd7-108">Ruft ab oder legt Liste der Latenz Details für jede der Zeitreihe.</span><span class="sxs-lookup"><span data-stu-id="c1dd7-108">Gets or sets list of latency details for each of the time series.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Provider">
      <MemberSignature Language="C#" Value="public string Provider { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Provider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.AzureReachabilityReportItem.Provider" />
      <MemberSignature Language="VB.NET" Value="Public Property Provider As String" />
      <MemberSignature Language="F#" Value="member this.Provider : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.AzureReachabilityReportItem.Provider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="provider")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c1dd7-109">Abrufen oder Festlegen der Internetdienstanbieter.</span><span class="sxs-lookup"><span data-stu-id="c1dd7-109">Gets or sets the Internet service provider.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>