<Type Name="EventModel" FullName="Microsoft.Azure.Management.ContainerRegistry.Models.EventModel">
  <TypeSignature Language="C#" Value="public class EventModel : Microsoft.Azure.Management.ContainerRegistry.Models.EventInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EventModel extends Microsoft.Azure.Management.ContainerRegistry.Models.EventInfo" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerRegistry.Models.EventModel" />
  <TypeSignature Language="VB.NET" Value="Public Class EventModel&#xA;Inherits EventInfo" />
  <TypeSignature Language="F#" Value="type EventModel = class&#xA;    inherit EventInfo" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ContainerRegistry.Models.EventInfo</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="91d90-101">Das Ereignis für einen Webhook.</span><span class="sxs-lookup"><span data-stu-id="91d90-101">The event for a webhook.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventModel ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.EventModel.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="91d90-102">Initialisiert eine neue Instanz der EventModel-Klasse.</span><span class="sxs-lookup"><span data-stu-id="91d90-102">Initializes a new instance of the EventModel class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventModel (string id = null, Microsoft.Azure.Management.ContainerRegistry.Models.EventRequestMessage eventRequestMessage = null, Microsoft.Azure.Management.ContainerRegistry.Models.EventResponseMessage eventResponseMessage = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, class Microsoft.Azure.Management.ContainerRegistry.Models.EventRequestMessage eventRequestMessage, class Microsoft.Azure.Management.ContainerRegistry.Models.EventResponseMessage eventResponseMessage) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.EventModel.#ctor(System.String,Microsoft.Azure.Management.ContainerRegistry.Models.EventRequestMessage,Microsoft.Azure.Management.ContainerRegistry.Models.EventResponseMessage)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ContainerRegistry.Models.EventModel : string * Microsoft.Azure.Management.ContainerRegistry.Models.EventRequestMessage * Microsoft.Azure.Management.ContainerRegistry.Models.EventResponseMessage -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.EventModel" Usage="new Microsoft.Azure.Management.ContainerRegistry.Models.EventModel (id, eventRequestMessage, eventResponseMessage)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="eventRequestMessage" Type="Microsoft.Azure.Management.ContainerRegistry.Models.EventRequestMessage" />
        <Parameter Name="eventResponseMessage" Type="Microsoft.Azure.Management.ContainerRegistry.Models.EventResponseMessage" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="91d90-103">Der Ereignis-ID</span><span class="sxs-lookup"><span data-stu-id="91d90-103">The event ID.</span></span></param>
        <param name="eventRequestMessage"><span data-ttu-id="91d90-104">Die Ereignis-Anforderungsnachricht gesendet, um den Dienst-URI.</span><span class="sxs-lookup"><span data-stu-id="91d90-104">The event request message sent to the service URI.</span></span></param>
        <param name="eventResponseMessage"><span data-ttu-id="91d90-105">Die Ereignis-Antwortnachricht empfangen aus dem Dienst-URI.</span><span class="sxs-lookup"><span data-stu-id="91d90-105">The event response message received from the service URI.</span></span></param>
        <summary>
            <span data-ttu-id="91d90-106">Initialisiert eine neue Instanz der EventModel-Klasse.</span><span class="sxs-lookup"><span data-stu-id="91d90-106">Initializes a new instance of the EventModel class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventRequestMessage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ContainerRegistry.Models.EventRequestMessage EventRequestMessage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ContainerRegistry.Models.EventRequestMessage EventRequestMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.EventModel.EventRequestMessage" />
      <MemberSignature Language="VB.NET" Value="Public Property EventRequestMessage As EventRequestMessage" />
      <MemberSignature Language="F#" Value="member this.EventRequestMessage : Microsoft.Azure.Management.ContainerRegistry.Models.EventRequestMessage with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.EventModel.EventRequestMessage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="eventRequestMessage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.EventRequestMessage</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="91d90-107">Ruft ab oder legt die Ereignis-Anforderungsnachricht gesendet, um den Dienst-URI.</span><span class="sxs-lookup"><span data-stu-id="91d90-107">Gets or sets the event request message sent to the service URI.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventResponseMessage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ContainerRegistry.Models.EventResponseMessage EventResponseMessage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ContainerRegistry.Models.EventResponseMessage EventResponseMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.EventModel.EventResponseMessage" />
      <MemberSignature Language="VB.NET" Value="Public Property EventResponseMessage As EventResponseMessage" />
      <MemberSignature Language="F#" Value="member this.EventResponseMessage : Microsoft.Azure.Management.ContainerRegistry.Models.EventResponseMessage with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.EventModel.EventResponseMessage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="eventResponseMessage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.EventResponseMessage</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="91d90-108">Ruft ab oder legt die Ereignis-Antwortnachricht empfangen aus dem Dienst-URI.</span><span class="sxs-lookup"><span data-stu-id="91d90-108">Gets or sets the event response message received from the service URI.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>