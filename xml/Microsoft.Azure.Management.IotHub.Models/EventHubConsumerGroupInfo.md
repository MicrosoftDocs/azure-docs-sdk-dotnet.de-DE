<Type Name="EventHubConsumerGroupInfo" FullName="Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo">
  <TypeSignature Language="C#" Value="public class EventHubConsumerGroupInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EventHubConsumerGroupInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class EventHubConsumerGroupInfo" />
  <TypeSignature Language="F#" Value="type EventHubConsumerGroupInfo = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="babec-101">Die Eigenschaften des Objekts EventHubConsumerGroupInfo.</span><span class="sxs-lookup"><span data-stu-id="babec-101">The properties of the EventHubConsumerGroupInfo object.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventHubConsumerGroupInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="babec-102">Initialisiert eine neue Instanz der EventHubConsumerGroupInfo-Klasse.</span><span class="sxs-lookup"><span data-stu-id="babec-102">Initializes a new instance of the EventHubConsumerGroupInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventHubConsumerGroupInfo (System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string id = null, string name = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string id, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo.#ctor(System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional tags As IDictionary(Of String, String) = null, Optional id As String = null, Optional name As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo : System.Collections.Generic.IDictionary&lt;string, string&gt; * string * string -&gt; Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo" Usage="new Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo (tags, id, name)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="tags"><span data-ttu-id="babec-103">Die Tags.</span><span class="sxs-lookup"><span data-stu-id="babec-103">The tags.</span></span></param>
        <param name="id"><span data-ttu-id="babec-104">Der Bezeichner der Event Hub-kompatiblen Consumer-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="babec-104">The Event Hub-compatible consumer group identifier.</span></span></param>
        <param name="name"><span data-ttu-id="babec-105">Der Name der Event Hub-kompatiblen Consumer-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="babec-105">The Event Hub-compatible consumer group name.</span></span></param>
        <summary>
            <span data-ttu-id="babec-106">Initialisiert eine neue Instanz der EventHubConsumerGroupInfo-Klasse.</span><span class="sxs-lookup"><span data-stu-id="babec-106">Initializes a new instance of the EventHubConsumerGroupInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
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
            <span data-ttu-id="babec-107">Abrufen oder Festlegen der Event Hub-kompatiblen Consumer Gruppenbezeichner.</span><span class="sxs-lookup"><span data-stu-id="babec-107">Gets or sets the Event Hub-compatible consumer group identifier.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="babec-108">Ruft ab oder legt der Consumer Event Hub-kompatiblen Gruppenname.</span><span class="sxs-lookup"><span data-stu-id="babec-108">Gets or sets the Event Hub-compatible consumer group name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tags")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="babec-109">Ruft ab oder legt die Tags.</span><span class="sxs-lookup"><span data-stu-id="babec-109">Gets or sets the tags.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>