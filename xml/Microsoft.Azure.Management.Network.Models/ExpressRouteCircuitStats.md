<Type Name="ExpressRouteCircuitStats" FullName="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats">
  <TypeSignature Language="C#" Value="public class ExpressRouteCircuitStats" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExpressRouteCircuitStats extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats" />
  <TypeSignature Language="VB.NET" Value="Public Class ExpressRouteCircuitStats" />
  <TypeSignature Language="F#" Value="type ExpressRouteCircuitStats = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="446c9-101">Enthält Statistiken, die das peering zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="446c9-101">Contains stats associated with the peering.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExpressRouteCircuitStats ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="446c9-102">Initialisiert eine neue Instanz der ExpressRouteCircuitStats-Klasse.</span><span class="sxs-lookup"><span data-stu-id="446c9-102">Initializes a new instance of the ExpressRouteCircuitStats class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExpressRouteCircuitStats (Nullable&lt;long&gt; primarybytesIn = null, Nullable&lt;long&gt; primarybytesOut = null, Nullable&lt;long&gt; secondarybytesIn = null, Nullable&lt;long&gt; secondarybytesOut = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int64&gt; primarybytesIn, valuetype System.Nullable`1&lt;int64&gt; primarybytesOut, valuetype System.Nullable`1&lt;int64&gt; secondarybytesIn, valuetype System.Nullable`1&lt;int64&gt; secondarybytesOut) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats.#ctor(System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional primarybytesIn As Nullable(Of Long) = null, Optional primarybytesOut As Nullable(Of Long) = null, Optional secondarybytesIn As Nullable(Of Long) = null, Optional secondarybytesOut As Nullable(Of Long) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats : Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; -&gt; Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats" Usage="new Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats (primarybytesIn, primarybytesOut, secondarybytesIn, secondarybytesOut)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="primarybytesIn" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="primarybytesOut" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="secondarybytesIn" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="secondarybytesOut" Type="System.Nullable&lt;System.Int64&gt;" />
      </Parameters>
      <Docs>
        <param name="primarybytesIn"><span data-ttu-id="446c9-103">Ruft die BytesIn von peering ab.</span><span class="sxs-lookup"><span data-stu-id="446c9-103">Gets BytesIn of the peering.</span></span></param>
        <param name="primarybytesOut"><span data-ttu-id="446c9-104">Ruft die BytesOut von peering ab.</span><span class="sxs-lookup"><span data-stu-id="446c9-104">Gets BytesOut of the peering.</span></span></param>
        <param name="secondarybytesIn"><span data-ttu-id="446c9-105">Ruft die BytesIn von peering ab.</span><span class="sxs-lookup"><span data-stu-id="446c9-105">Gets BytesIn of the peering.</span></span></param>
        <param name="secondarybytesOut"><span data-ttu-id="446c9-106">Ruft die BytesOut von peering ab.</span><span class="sxs-lookup"><span data-stu-id="446c9-106">Gets BytesOut of the peering.</span></span></param>
        <summary>
            <span data-ttu-id="446c9-107">Initialisiert eine neue Instanz der ExpressRouteCircuitStats-Klasse.</span><span class="sxs-lookup"><span data-stu-id="446c9-107">Initializes a new instance of the ExpressRouteCircuitStats class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimarybytesIn">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; PrimarybytesIn { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; PrimarybytesIn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats.PrimarybytesIn" />
      <MemberSignature Language="VB.NET" Value="Public Property PrimarybytesIn As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.PrimarybytesIn : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats.PrimarybytesIn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="primarybytesIn")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="446c9-108">Ruft die BytesIn von peering ab.</span><span class="sxs-lookup"><span data-stu-id="446c9-108">Gets BytesIn of the peering.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimarybytesOut">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; PrimarybytesOut { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; PrimarybytesOut" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats.PrimarybytesOut" />
      <MemberSignature Language="VB.NET" Value="Public Property PrimarybytesOut As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.PrimarybytesOut : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats.PrimarybytesOut" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="primarybytesOut")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="446c9-109">Ruft die BytesOut von peering ab.</span><span class="sxs-lookup"><span data-stu-id="446c9-109">Gets BytesOut of the peering.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondarybytesIn">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; SecondarybytesIn { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; SecondarybytesIn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats.SecondarybytesIn" />
      <MemberSignature Language="VB.NET" Value="Public Property SecondarybytesIn As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.SecondarybytesIn : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats.SecondarybytesIn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="secondarybytesIn")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="446c9-110">Ruft die BytesIn von peering ab.</span><span class="sxs-lookup"><span data-stu-id="446c9-110">Gets BytesIn of the peering.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondarybytesOut">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; SecondarybytesOut { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; SecondarybytesOut" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats.SecondarybytesOut" />
      <MemberSignature Language="VB.NET" Value="Public Property SecondarybytesOut As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.SecondarybytesOut : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats.SecondarybytesOut" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="secondarybytesOut")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="446c9-111">Ruft die BytesOut von peering ab.</span><span class="sxs-lookup"><span data-stu-id="446c9-111">Gets BytesOut of the peering.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>