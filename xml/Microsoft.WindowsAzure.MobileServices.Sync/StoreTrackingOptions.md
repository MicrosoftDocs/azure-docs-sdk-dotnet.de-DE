<Type Name="StoreTrackingOptions" FullName="Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions">
  <TypeSignature Language="C#" Value="public enum StoreTrackingOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed StoreTrackingOptions extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions" />
  <TypeSignature Language="VB.NET" Value="Public Enum StoreTrackingOptions" />
  <TypeSignature Language="F#" Value="type StoreTrackingOptions = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Attributes>
    <Attribute>
      <AttributeName>System.Flags</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="52553-101">Eine Flags-Enumeration für den verfügbaren Speicher Überwachungsoptionen verfügbar.</span><span class="sxs-lookup"><span data-stu-id="52553-101">A flags enumeration for the available store tracking options available.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AllNotifications">
      <MemberSignature Language="C#" Value="AllNotifications" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions AllNotifications = int32(63)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.AllNotifications" />
      <MemberSignature Language="VB.NET" Value="AllNotifications" />
      <MemberSignature Language="F#" Value="AllNotifications = 63" Usage="Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.AllNotifications" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions</ReturnType>
      </ReturnValue>
      <MemberValue>63</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="52553-102">Alle Vorgänge aufzuzeichnen und Batch Benachrichtigungen generiert.</span><span class="sxs-lookup"><span data-stu-id="52553-102">Generates all record operations and batch notifications.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="AllNotificationsAndChangeDetection">
      <MemberSignature Language="C#" Value="AllNotificationsAndChangeDetection" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions AllNotificationsAndChangeDetection = int32(255)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.AllNotificationsAndChangeDetection" />
      <MemberSignature Language="VB.NET" Value="AllNotificationsAndChangeDetection" />
      <MemberSignature Language="F#" Value="AllNotificationsAndChangeDetection = 255" Usage="Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.AllNotificationsAndChangeDetection" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions</ReturnType>
      </ReturnValue>
      <MemberValue>255</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="52553-103">Alle Datensätze Vorgang Benachrichtigungen generiert, batch-Benachrichtigungen, einfügen und änderungserkennung für die Erkennung und Datensatz aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="52553-103">Generates all record operation notifications, batch notifications, insert and updates detection and record change detection.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="DetectInsertsAndUpdates">
      <MemberSignature Language="C#" Value="DetectInsertsAndUpdates" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions DetectInsertsAndUpdates = int32(64)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.DetectInsertsAndUpdates" />
      <MemberSignature Language="VB.NET" Value="DetectInsertsAndUpdates" />
      <MemberSignature Language="F#" Value="DetectInsertsAndUpdates = 64" Usage="Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.DetectInsertsAndUpdates" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions</ReturnType>
      </ReturnValue>
      <MemberValue>64</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="52553-104">Aktivieren Sie "Upsert" Analyse zu erkennen, ob der Datensatz wird erstellt oder aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="52553-104">Enable "upsert" analysis to detect if the record is being created or updated.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="DetectRecordChanges">
      <MemberSignature Language="C#" Value="DetectRecordChanges" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions DetectRecordChanges = int32(192)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.DetectRecordChanges" />
      <MemberSignature Language="VB.NET" Value="DetectRecordChanges" />
      <MemberSignature Language="F#" Value="DetectRecordChanges = 192" Usage="Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.DetectRecordChanges" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions</ReturnType>
      </ReturnValue>
      <MemberValue>192</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="52553-105">Auf Updates aktivieren Erkennung Datensätze zu ändern und nur Benachrichtigungen generiert, wenn Änderungen erkannt werden.</span><span class="sxs-lookup"><span data-stu-id="52553-105">On updates, enable change detection on records and only generates notifications if data changes are detected.</span></span>
            <span data-ttu-id="52553-106">Dies ermöglicht eingefügt und aktualisiert automatisch Analyse.</span><span class="sxs-lookup"><span data-stu-id="52553-106">This automatically enables inserts and updates analysis.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="None" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions None = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.None" />
      <MemberSignature Language="VB.NET" Value="None" />
      <MemberSignature Language="F#" Value="None = 0" Usage="Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="52553-107">Keine Überwachungsoptionen.</span><span class="sxs-lookup"><span data-stu-id="52553-107">No tracking options.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="NotifyLocalAndServerOperations">
      <MemberSignature Language="C#" Value="NotifyLocalAndServerOperations" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions NotifyLocalAndServerOperations = int32(15)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.NotifyLocalAndServerOperations" />
      <MemberSignature Language="VB.NET" Value="NotifyLocalAndServerOperations" />
      <MemberSignature Language="F#" Value="NotifyLocalAndServerOperations = 15" Usage="Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.NotifyLocalAndServerOperations" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions</ReturnType>
      </ReturnValue>
      <MemberValue>15</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="52553-108">Generiert Benachrichtigungen für lokale und (Pull oder Push) Datensatz Servervorgänge.</span><span class="sxs-lookup"><span data-stu-id="52553-108">Generates notifications for local and server (pull or push) record operations.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="NotifyLocalConflictResolutionOperations">
      <MemberSignature Language="C#" Value="NotifyLocalConflictResolutionOperations" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions NotifyLocalConflictResolutionOperations = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.NotifyLocalConflictResolutionOperations" />
      <MemberSignature Language="VB.NET" Value="NotifyLocalConflictResolutionOperations" />
      <MemberSignature Language="F#" Value="NotifyLocalConflictResolutionOperations = 2" Usage="Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.NotifyLocalConflictResolutionOperations" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="52553-109">Generiert Benachrichtigungen für lokale Konflikt auflösen Datensatz Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="52553-109">Generates notifications for local conflict resolution record operations.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="NotifyLocalOperations">
      <MemberSignature Language="C#" Value="NotifyLocalOperations" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions NotifyLocalOperations = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.NotifyLocalOperations" />
      <MemberSignature Language="VB.NET" Value="NotifyLocalOperations" />
      <MemberSignature Language="F#" Value="NotifyLocalOperations = 1" Usage="Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.NotifyLocalOperations" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="52553-110">Generiert Benachrichtigungen für lokalen Datensatz Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="52553-110">Generates notifications for local record operations.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="NotifyServerBatch">
      <MemberSignature Language="C#" Value="NotifyServerBatch" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions NotifyServerBatch = int32(48)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.NotifyServerBatch" />
      <MemberSignature Language="VB.NET" Value="NotifyServerBatch" />
      <MemberSignature Language="F#" Value="NotifyServerBatch = 48" Usage="Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.NotifyServerBatch" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions</ReturnType>
      </ReturnValue>
      <MemberValue>48</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="52553-111">Generiert eine Benachrichtigung an das Ende eines Vorgangs Batches von einem Server Pull oder ein Serverpush-ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="52553-111">Generates a notification at the end of an operation batch triggered by a server pull or a server push.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="NotifyServerOperations">
      <MemberSignature Language="C#" Value="NotifyServerOperations" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions NotifyServerOperations = int32(12)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.NotifyServerOperations" />
      <MemberSignature Language="VB.NET" Value="NotifyServerOperations" />
      <MemberSignature Language="F#" Value="NotifyServerOperations = 12" Usage="Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.NotifyServerOperations" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions</ReturnType>
      </ReturnValue>
      <MemberValue>12</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="52553-112">Generiert Benachrichtigungen für Vorgänge in Kürze von einem Server Pull oder ein Serverpush-an.</span><span class="sxs-lookup"><span data-stu-id="52553-112">Generates notifications for operations triggerd by a server pull or a server push.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="NotifyServerPullBatch">
      <MemberSignature Language="C#" Value="NotifyServerPullBatch" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions NotifyServerPullBatch = int32(16)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.NotifyServerPullBatch" />
      <MemberSignature Language="VB.NET" Value="NotifyServerPullBatch" />
      <MemberSignature Language="F#" Value="NotifyServerPullBatch = 16" Usage="Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.NotifyServerPullBatch" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions</ReturnType>
      </ReturnValue>
      <MemberValue>16</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="52553-113">Generiert eine Benachrichtigung am Ende eines Vorgangs Batches durch einen Pull Server ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="52553-113">Generates a notification at the end of an operation batch triggered by a server pull.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="NotifyServerPullOperations">
      <MemberSignature Language="C#" Value="NotifyServerPullOperations" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions NotifyServerPullOperations = int32(4)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.NotifyServerPullOperations" />
      <MemberSignature Language="VB.NET" Value="NotifyServerPullOperations" />
      <MemberSignature Language="F#" Value="NotifyServerPullOperations = 4" Usage="Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.NotifyServerPullOperations" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="52553-114">Generiert Benachrichtigungen für Vorgänge, die von einem Server Pull ausgelöst werden.</span><span class="sxs-lookup"><span data-stu-id="52553-114">Generates notifications for operations triggered by a server pull.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="NotifyServerPushBatch">
      <MemberSignature Language="C#" Value="NotifyServerPushBatch" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions NotifyServerPushBatch = int32(32)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.NotifyServerPushBatch" />
      <MemberSignature Language="VB.NET" Value="NotifyServerPushBatch" />
      <MemberSignature Language="F#" Value="NotifyServerPushBatch = 32" Usage="Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.NotifyServerPushBatch" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions</ReturnType>
      </ReturnValue>
      <MemberValue>32</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="52553-115">Generiert eine Benachrichtigung am Ende eines Vorgangs Batches durch ein Serverpush ausgelöst wird.</span><span class="sxs-lookup"><span data-stu-id="52553-115">Generates a notification at the end of an operation batch triggered by a server push.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="NotifyServerPushOperations">
      <MemberSignature Language="C#" Value="NotifyServerPushOperations" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions NotifyServerPushOperations = int32(8)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.NotifyServerPushOperations" />
      <MemberSignature Language="VB.NET" Value="NotifyServerPushOperations" />
      <MemberSignature Language="F#" Value="NotifyServerPushOperations = 8" Usage="Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.NotifyServerPushOperations" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions</ReturnType>
      </ReturnValue>
      <MemberValue>8</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="52553-116">Generiert Notifiactions für Vorgänge, die durch ein Serverpush ausgelöst wird.</span><span class="sxs-lookup"><span data-stu-id="52553-116">Generates notifiactions for operations triggered by a server push.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>