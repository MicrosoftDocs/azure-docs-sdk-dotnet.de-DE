<Type Name="ExpressRouteCircuitArpTable" FullName="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitArpTable">
  <TypeSignature Language="C#" Value="public class ExpressRouteCircuitArpTable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExpressRouteCircuitArpTable extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitArpTable" />
  <TypeSignature Language="VB.NET" Value="Public Class ExpressRouteCircuitArpTable" />
  <TypeSignature Language="F#" Value="type ExpressRouteCircuitArpTable = class" />
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
            <span data-ttu-id="bf71f-101">Der ARP-Tabelle der ExpressRouteCircuit zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="bf71f-101">The ARP table associated with the ExpressRouteCircuit.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExpressRouteCircuitArpTable ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitArpTable.#ctor" />
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
            <span data-ttu-id="bf71f-102">Initialisiert eine neue Instanz der ExpressRouteCircuitArpTable-Klasse.</span><span class="sxs-lookup"><span data-stu-id="bf71f-102">Initializes a new instance of the ExpressRouteCircuitArpTable class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExpressRouteCircuitArpTable (Nullable&lt;int&gt; age = null, string interfaceProperty = null, string ipAddress = null, string macAddress = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; age, string interfaceProperty, string ipAddress, string macAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitArpTable.#ctor(System.Nullable{System.Int32},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional age As Nullable(Of Integer) = null, Optional interfaceProperty As String = null, Optional ipAddress As String = null, Optional macAddress As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitArpTable : Nullable&lt;int&gt; * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitArpTable" Usage="new Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitArpTable (age, interfaceProperty, ipAddress, macAddress)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="age" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="interfaceProperty" Type="System.String" />
        <Parameter Name="ipAddress" Type="System.String" />
        <Parameter Name="macAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="age"><span data-ttu-id="bf71f-103">Alter</span><span class="sxs-lookup"><span data-stu-id="bf71f-103">Age</span></span></param>
        <param name="interfaceProperty"><span data-ttu-id="bf71f-104">Schnittstelle</span><span class="sxs-lookup"><span data-stu-id="bf71f-104">Interface</span></span></param>
        <param name="ipAddress"><span data-ttu-id="bf71f-105">Die IP-Adresse.</span><span class="sxs-lookup"><span data-stu-id="bf71f-105">The IP address.</span></span></param>
        <param name="macAddress"><span data-ttu-id="bf71f-106">Die MAC-Adresse.</span><span class="sxs-lookup"><span data-stu-id="bf71f-106">The MAC address.</span></span></param>
        <summary>
            <span data-ttu-id="bf71f-107">Initialisiert eine neue Instanz der ExpressRouteCircuitArpTable-Klasse.</span><span class="sxs-lookup"><span data-stu-id="bf71f-107">Initializes a new instance of the ExpressRouteCircuitArpTable class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Age">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Age { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Age" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitArpTable.Age" />
      <MemberSignature Language="VB.NET" Value="Public Property Age As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Age : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitArpTable.Age" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="age")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf71f-108">Ruft ab oder legt ihn fest ALTER</span><span class="sxs-lookup"><span data-stu-id="bf71f-108">Gets or sets age</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InterfaceProperty">
      <MemberSignature Language="C#" Value="public string InterfaceProperty { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InterfaceProperty" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitArpTable.InterfaceProperty" />
      <MemberSignature Language="VB.NET" Value="Public Property InterfaceProperty As String" />
      <MemberSignature Language="F#" Value="member this.InterfaceProperty : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitArpTable.InterfaceProperty" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="interface")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf71f-109">Ruft ab oder legt-Schnittstelle</span><span class="sxs-lookup"><span data-stu-id="bf71f-109">Gets or sets interface</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IpAddress">
      <MemberSignature Language="C#" Value="public string IpAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IpAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitArpTable.IpAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property IpAddress As String" />
      <MemberSignature Language="F#" Value="member this.IpAddress : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitArpTable.IpAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ipAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf71f-110">Ruft ab oder legt die IP-Adresse.</span><span class="sxs-lookup"><span data-stu-id="bf71f-110">Gets or sets the IP address.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MacAddress">
      <MemberSignature Language="C#" Value="public string MacAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MacAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitArpTable.MacAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property MacAddress As String" />
      <MemberSignature Language="F#" Value="member this.MacAddress : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitArpTable.MacAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="macAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf71f-111">Ruft ab oder legt die MAC-Adresse.</span><span class="sxs-lookup"><span data-stu-id="bf71f-111">Gets or sets the MAC address.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>