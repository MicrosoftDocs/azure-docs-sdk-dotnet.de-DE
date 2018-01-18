<Type Name="ScheduledNotification" FullName="Microsoft.Azure.NotificationHubs.ScheduledNotification">
  <TypeSignature Language="C#" Value="public class ScheduledNotification" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ScheduledNotification extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.ScheduledNotification" />
  <TypeSignature Language="VB.NET" Value="Public Class ScheduledNotification" />
  <TypeSignature Language="F#" Value="type ScheduledNotification = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="ScheduledNotification", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary><span data-ttu-id="52f95-101">Stellt den geplanten <see cref="T:Microsoft.Azure.NotificationHubs.Notification" />.</span><span class="sxs-lookup"><span data-stu-id="52f95-101">Represents the scheduled <see cref="T:Microsoft.Azure.NotificationHubs.Notification" />.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ScheduledNotification ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.ScheduledNotification.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="52f95-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.ScheduledNotification" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="52f95-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.ScheduledNotification" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Payload">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.Notification Payload { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.NotificationHubs.Notification Payload" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ScheduledNotification.Payload" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Payload As Notification" />
      <MemberSignature Language="F#" Value="member this.Payload : Microsoft.Azure.NotificationHubs.Notification" Usage="Microsoft.Azure.NotificationHubs.ScheduledNotification.Payload" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=true, IsRequired=true, Name="Payload", Order=1001)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Notification</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="52f95-103">Ruft ab oder legt die Nutzlast dieser geplante Benachrichtigung.</span><span class="sxs-lookup"><span data-stu-id="52f95-103">Gets or sets the payload of this scheduled notification.</span></span></summary>
        <value><span data-ttu-id="52f95-104">Die Nutzlast dieser geplante Benachrichtigung.</span><span class="sxs-lookup"><span data-stu-id="52f95-104">The payload of this scheduled notification.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduledNotificationId">
      <MemberSignature Language="C#" Value="public string ScheduledNotificationId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ScheduledNotificationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ScheduledNotification.ScheduledNotificationId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ScheduledNotificationId As String" />
      <MemberSignature Language="F#" Value="member this.ScheduledNotificationId : string" Usage="Microsoft.Azure.NotificationHubs.ScheduledNotification.ScheduledNotificationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=true, IsRequired=true, Name="ScheduledNotificationId", Order=1002)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="52f95-105">Ruft ab oder legt den Bezeichner für die Benachrichtigung.</span><span class="sxs-lookup"><span data-stu-id="52f95-105">Gets or sets the notification identifier.</span></span></summary>
        <value><span data-ttu-id="52f95-106">Die benachrichtigungs-ID.</span><span class="sxs-lookup"><span data-stu-id="52f95-106">The notification identifier.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduledTime">
      <MemberSignature Language="C#" Value="public DateTimeOffset ScheduledTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTimeOffset ScheduledTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ScheduledNotification.ScheduledTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ScheduledTime As DateTimeOffset" />
      <MemberSignature Language="F#" Value="member this.ScheduledTime : DateTimeOffset" Usage="Microsoft.Azure.NotificationHubs.ScheduledNotification.ScheduledTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=true, IsRequired=true, Name="ScheduledTime", Order=1003)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTimeOffset</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="52f95-107">Ruft ab oder legt dem geplanten Zeitpunkt.</span><span class="sxs-lookup"><span data-stu-id="52f95-107">Gets or sets the scheduled time.</span></span></summary>
        <value><span data-ttu-id="52f95-108">Die geplante Zeit.</span><span class="sxs-lookup"><span data-stu-id="52f95-108">The scheduled time.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public string Tags { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ScheduledNotification.Tags" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Tags As String" />
      <MemberSignature Language="F#" Value="member this.Tags : string" Usage="Microsoft.Azure.NotificationHubs.ScheduledNotification.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=true, IsRequired=true, Name="Tags", Order=1004)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="52f95-109">Abrufen oder Festlegen der Benachrichtigung-Tag.</span><span class="sxs-lookup"><span data-stu-id="52f95-109">Gets or sets the notification tag.</span></span></summary>
        <value><span data-ttu-id="52f95-110">Die Benachrichtigung-Tag.</span><span class="sxs-lookup"><span data-stu-id="52f95-110">The notification tag.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrackingId">
      <MemberSignature Language="C#" Value="public string TrackingId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TrackingId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ScheduledNotification.TrackingId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TrackingId As String" />
      <MemberSignature Language="F#" Value="member this.TrackingId : string" Usage="Microsoft.Azure.NotificationHubs.ScheduledNotification.TrackingId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=true, IsRequired=true, Name="TrackingId", Order=1005)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="52f95-111">Abrufen oder festlegen den Bezeichner für die Überwachung.</span><span class="sxs-lookup"><span data-stu-id="52f95-111">Gets or sets the tracking identifier.</span></span></summary>
        <value><span data-ttu-id="52f95-112">Der Überwachungsprofil-Bezeichner.</span><span class="sxs-lookup"><span data-stu-id="52f95-112">The tracking identifier.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>