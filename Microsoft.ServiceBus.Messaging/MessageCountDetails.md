<Type Name="MessageCountDetails" FullName="Microsoft.ServiceBus.Messaging.MessageCountDetails">
  <TypeSignature Language="C#" Value="public sealed class MessageCountDetails" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit MessageCountDetails extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.MessageCountDetails" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class MessageCountDetails" />
  <TypeSignature Language="F#" Value="type MessageCountDetails = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="MessageCountDetails", Namespace="http://schemas.microsoft.com/netservices/2011/06/servicebus")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>Diese Klasse enthält Eigenschaften, die Sie beim Abrufen der Details von Nachrichten aus Unterwarteschlangen der primären messagingentitäten (Warteschlangen, Themen, Abonnements) ermöglichen.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessageCountDetails ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageCountDetails.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.MessageCountDetails" />-Klasse.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessageCountDetails (long activeMessageCount, long deadletterMessageCount, long scheduledMessageCount, long transferMessageCount, long transferDlqMessageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int64 activeMessageCount, int64 deadletterMessageCount, int64 scheduledMessageCount, int64 transferMessageCount, int64 transferDlqMessageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageCountDetails.#ctor(System.Int64,System.Int64,System.Int64,System.Int64,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (activeMessageCount As Long, deadletterMessageCount As Long, scheduledMessageCount As Long, transferMessageCount As Long, transferDlqMessageCount As Long)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.MessageCountDetails : int64 * int64 * int64 * int64 * int64 -&gt; Microsoft.ServiceBus.Messaging.MessageCountDetails" Usage="new Microsoft.ServiceBus.Messaging.MessageCountDetails (activeMessageCount, deadletterMessageCount, scheduledMessageCount, transferMessageCount, transferDlqMessageCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="activeMessageCount" Type="System.Int64" />
        <Parameter Name="deadletterMessageCount" Type="System.Int64" />
        <Parameter Name="scheduledMessageCount" Type="System.Int64" />
        <Parameter Name="transferMessageCount" Type="System.Int64" />
        <Parameter Name="transferDlqMessageCount" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="activeMessageCount">Die Anzahl der aktiven Nachrichten.</param>
        <param name="deadletterMessageCount">Die Anzahl der unzustellbare Nachrichten.</param>
        <param name="scheduledMessageCount">Die Anzahl der geplanten Nachrichten.</param>
        <param name="transferMessageCount">Die Anzahl der Nachrichten, die in anderen Warteschlangen, Abonnements oder Themen übertragen werden.</param>
        <param name="transferDlqMessageCount">Die Anzahl der Nachrichten an die Dead Letter-Warteschlange übertragen.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.MessageCountDetails" /> Klasse mit der Anzahl der aktiven Nachrichten, unzustellbare Nachrichten, geplante Nachrichten, Nachrichten an andere Warteschlangen, Abonnements oder Themen zu übertragen, und die Anzahl der Nachrichten an die Dead Letter-Warteschlange zu übertragen.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActiveMessageCount">
      <MemberSignature Language="C#" Value="public long ActiveMessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ActiveMessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageCountDetails.ActiveMessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActiveMessageCount As Long" />
      <MemberSignature Language="F#" Value="member this.ActiveMessageCount : int64" Usage="Microsoft.ServiceBus.Messaging.MessageCountDetails.ActiveMessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(Order=65537)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die Anzahl der aktiven Nachrichten in der Warteschlange, Thema oder Abonnement fest.</summary>
        <value>Gibt <see cref="T:System.Int64" /> , die die Anzahl der aktiven Nachrichten angibt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterMessageCount">
      <MemberSignature Language="C#" Value="public long DeadLetterMessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DeadLetterMessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageCountDetails.DeadLetterMessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeadLetterMessageCount As Long" />
      <MemberSignature Language="F#" Value="member this.DeadLetterMessageCount : int64" Usage="Microsoft.ServiceBus.Messaging.MessageCountDetails.DeadLetterMessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(Order=65538)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die Anzahl der Nachrichten, die Warteschlange für unzustellbare Nachrichten Buchstaben darstellen.</summary>
        <value>Gibt <see cref="T:System.Int64" />, die die Anzahl der Nachrichten, die unzustellbare Nachrichten angibt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduledMessageCount">
      <MemberSignature Language="C#" Value="public long ScheduledMessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ScheduledMessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageCountDetails.ScheduledMessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ScheduledMessageCount As Long" />
      <MemberSignature Language="F#" Value="member this.ScheduledMessageCount : int64" Usage="Microsoft.ServiceBus.Messaging.MessageCountDetails.ScheduledMessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(Order=65539)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die Anzahl geplanten Nachrichten.</summary>
        <value>Gibt <see cref="T:System.Int64" />die Anzahl der geplanten Nachrichten.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransferDeadLetterMessageCount">
      <MemberSignature Language="C#" Value="public long TransferDeadLetterMessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TransferDeadLetterMessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageCountDetails.TransferDeadLetterMessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TransferDeadLetterMessageCount As Long" />
      <MemberSignature Language="F#" Value="member this.TransferDeadLetterMessageCount : int64" Usage="Microsoft.ServiceBus.Messaging.MessageCountDetails.TransferDeadLetterMessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(Order=65541)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die Anzahl Nachrichten, die in der unzustellbare Nachrichten übertragen.</summary>
        <value>Gibt <see cref="T:System.Int64" />, die die Anzahl, in der unzustellbare Nachrichten übertragenen Nachrichten angibt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransferMessageCount">
      <MemberSignature Language="C#" Value="public long TransferMessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TransferMessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageCountDetails.TransferMessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TransferMessageCount As Long" />
      <MemberSignature Language="F#" Value="member this.TransferMessageCount : int64" Usage="Microsoft.ServiceBus.Messaging.MessageCountDetails.TransferMessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(Order=65540)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die Anzahl der Nachrichten, die in einer anderen Warteschlange, Thema oder Abonnement übertragen.</summary>
        <value>Gibt <see cref="T:System.Int64" />, der angibt, dass der Anzahl der Nachrichten, die in einer anderen Warteschlange, Thema oder Abonnement übertragen</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>