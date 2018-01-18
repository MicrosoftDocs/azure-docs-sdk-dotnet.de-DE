<Type Name="MessageCountDetails" FullName="Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails">
  <TypeSignature Language="C#" Value="public class MessageCountDetails" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MessageCountDetails extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails" />
  <TypeSignature Language="VB.NET" Value="Public Class MessageCountDetails" />
  <TypeSignature Language="F#" Value="type MessageCountDetails = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="482ea-101">Details zur Nachrichtenanzahl.</span><span class="sxs-lookup"><span data-stu-id="482ea-101">Message Count Details.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessageCountDetails ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="482ea-102">Initialisiert eine neue Instanz der MessageCountDetails-Klasse.</span><span class="sxs-lookup"><span data-stu-id="482ea-102">Initializes a new instance of the MessageCountDetails class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessageCountDetails (Nullable&lt;long&gt; activeMessageCount = null, Nullable&lt;long&gt; deadLetterMessageCount = null, Nullable&lt;long&gt; scheduledMessageCount = null, Nullable&lt;long&gt; transferMessageCount = null, Nullable&lt;long&gt; transferDeadLetterMessageCount = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int64&gt; activeMessageCount, valuetype System.Nullable`1&lt;int64&gt; deadLetterMessageCount, valuetype System.Nullable`1&lt;int64&gt; scheduledMessageCount, valuetype System.Nullable`1&lt;int64&gt; transferMessageCount, valuetype System.Nullable`1&lt;int64&gt; transferDeadLetterMessageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails.#ctor(System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional activeMessageCount As Nullable(Of Long) = null, Optional deadLetterMessageCount As Nullable(Of Long) = null, Optional scheduledMessageCount As Nullable(Of Long) = null, Optional transferMessageCount As Nullable(Of Long) = null, Optional transferDeadLetterMessageCount As Nullable(Of Long) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails : Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; -&gt; Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails" Usage="new Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails (activeMessageCount, deadLetterMessageCount, scheduledMessageCount, transferMessageCount, transferDeadLetterMessageCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="activeMessageCount" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="deadLetterMessageCount" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="scheduledMessageCount" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="transferMessageCount" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="transferDeadLetterMessageCount" Type="System.Nullable&lt;System.Int64&gt;" />
      </Parameters>
      <Docs>
        <param name="activeMessageCount"><span data-ttu-id="482ea-103">Die Anzahl der aktiven Nachrichten in der Warteschlange, Thema oder Abonnement.</span><span class="sxs-lookup"><span data-stu-id="482ea-103">Number of active messages in the queue, topic, or subscription.</span></span></param>
        <param name="deadLetterMessageCount"><span data-ttu-id="482ea-104">Anzahl der Nachrichten, die Warteschlange für unzustellbare Nachrichten Übermittlungsversuchen sind.</span><span class="sxs-lookup"><span data-stu-id="482ea-104">Number of messages that are dead lettered.</span></span></param>
        <param name="scheduledMessageCount"><span data-ttu-id="482ea-105">Anzahl der geplanten Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="482ea-105">Number of scheduled messages.</span></span></param>
        <param name="transferMessageCount"><span data-ttu-id="482ea-106">Anzahl der Nachrichten, die in einer anderen Warteschlange, Thema oder Abonnement übertragen werden.</span><span class="sxs-lookup"><span data-stu-id="482ea-106">Number of messages transferred to another queue, topic, or subscription.</span></span></param>
        <param name="transferDeadLetterMessageCount"><span data-ttu-id="482ea-107">Anzahl der Nachrichten, die in der unzustellbare Nachrichten übertragen werden.</span><span class="sxs-lookup"><span data-stu-id="482ea-107">Number of messages transferred into dead letters.</span></span></param>
        <summary>
            <span data-ttu-id="482ea-108">Initialisiert eine neue Instanz der MessageCountDetails-Klasse.</span><span class="sxs-lookup"><span data-stu-id="482ea-108">Initializes a new instance of the MessageCountDetails class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActiveMessageCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; ActiveMessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; ActiveMessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails.ActiveMessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActiveMessageCount As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.ActiveMessageCount : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails.ActiveMessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="activeMessageCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="482ea-109">Ruft die Anzahl der aktiven Nachrichten in der Warteschlange, Thema oder Abonnement.</span><span class="sxs-lookup"><span data-stu-id="482ea-109">Gets number of active messages in the queue, topic, or subscription.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterMessageCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; DeadLetterMessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; DeadLetterMessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails.DeadLetterMessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeadLetterMessageCount As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.DeadLetterMessageCount : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails.DeadLetterMessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="deadLetterMessageCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="482ea-110">Ruft die Anzahl der Nachrichten, die Warteschlange für unzustellbare Nachrichten Übermittlungsversuchen sind.</span><span class="sxs-lookup"><span data-stu-id="482ea-110">Gets number of messages that are dead lettered.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduledMessageCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; ScheduledMessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; ScheduledMessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails.ScheduledMessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ScheduledMessageCount As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.ScheduledMessageCount : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails.ScheduledMessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="scheduledMessageCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="482ea-111">Ruft die Anzahl der geplanten Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="482ea-111">Gets number of scheduled messages.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransferDeadLetterMessageCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; TransferDeadLetterMessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; TransferDeadLetterMessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails.TransferDeadLetterMessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TransferDeadLetterMessageCount As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.TransferDeadLetterMessageCount : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails.TransferDeadLetterMessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="transferDeadLetterMessageCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="482ea-112">Ruft die Anzahl der Nachrichten, die in der unzustellbare Nachrichten übertragen werden.</span><span class="sxs-lookup"><span data-stu-id="482ea-112">Gets number of messages transferred into dead letters.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransferMessageCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; TransferMessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; TransferMessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails.TransferMessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TransferMessageCount As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.TransferMessageCount : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails.TransferMessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="transferMessageCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="482ea-113">Ruft die Anzahl der Nachrichten, die in einer anderen Warteschlange, Thema oder Abonnement übertragen werden.</span><span class="sxs-lookup"><span data-stu-id="482ea-113">Gets number of messages transferred to another queue, topic, or subscription.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>