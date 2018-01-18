<Type Name="ChangeFeedObserverCloseReason" FullName="Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverCloseReason">
  <TypeSignature Language="C#" Value="public enum ChangeFeedObserverCloseReason" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ChangeFeedObserverCloseReason extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverCloseReason" />
  <TypeSignature Language="VB.NET" Value="Public Enum ChangeFeedObserverCloseReason" />
  <TypeSignature Language="F#" Value="type ChangeFeedObserverCloseReason = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
    <AssemblyVersion>1.17.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="93963-101">Der Grund, warum eine Instanz von "Beobachter" geschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="93963-101">The reason why an instance of Observer is closed.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="LeaseGone">
      <MemberSignature Language="C#" Value="LeaseGone" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverCloseReason LeaseGone = int32(5)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverCloseReason.LeaseGone" />
      <MemberSignature Language="VB.NET" Value="LeaseGone" />
      <MemberSignature Language="F#" Value="LeaseGone = 5" Usage="Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverCloseReason.LeaseGone" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverCloseReason</ReturnType>
      </ReturnValue>
      <MemberValue>5</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="93963-102">Die Lease ist nicht mehr vorhanden.</span><span class="sxs-lookup"><span data-stu-id="93963-102">The lease is gone.</span></span> <span data-ttu-id="93963-103">Dies kann aufgrund von Teilen der Partition sein.</span><span class="sxs-lookup"><span data-stu-id="93963-103">This can be due to partition split.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="LeaseLost">
      <MemberSignature Language="C#" Value="LeaseLost" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverCloseReason LeaseLost = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverCloseReason.LeaseLost" />
      <MemberSignature Language="VB.NET" Value="LeaseLost" />
      <MemberSignature Language="F#" Value="LeaseLost = 3" Usage="Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverCloseReason.LeaseLost" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverCloseReason</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="93963-104">Lease wurde unterbrochen, aufgrund der abgelaufene oder Lastenausgleich.</span><span class="sxs-lookup"><span data-stu-id="93963-104">Lease was lost due to expiration or load-balancing.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="ObserverError">
      <MemberSignature Language="C#" Value="ObserverError" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverCloseReason ObserverError = int32(4)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverCloseReason.ObserverError" />
      <MemberSignature Language="VB.NET" Value="ObserverError" />
      <MemberSignature Language="F#" Value="ObserverError = 4" Usage="Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverCloseReason.ObserverError" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverCloseReason</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="93963-105">IChangeFeedObserver hat eine Ausnahme ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="93963-105">IChangeFeedObserver threw an exception.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="ResourceGone">
      <MemberSignature Language="C#" Value="ResourceGone" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverCloseReason ResourceGone = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverCloseReason.ResourceGone" />
      <MemberSignature Language="VB.NET" Value="ResourceGone" />
      <MemberSignature Language="F#" Value="ResourceGone = 2" Usage="Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverCloseReason.ResourceGone" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverCloseReason</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="93963-106">Die Ressource, z. B. Datenbank- oder Auflistung entfernt wurde.</span><span class="sxs-lookup"><span data-stu-id="93963-106">The resource, such as database or collection was removed.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Shutdown">
      <MemberSignature Language="C#" Value="Shutdown" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverCloseReason Shutdown = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverCloseReason.Shutdown" />
      <MemberSignature Language="VB.NET" Value="Shutdown" />
      <MemberSignature Language="F#" Value="Shutdown = 1" Usage="Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverCloseReason.Shutdown" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverCloseReason</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="93963-107">Die ChangeFeedEventHost wird heruntergefahren.</span><span class="sxs-lookup"><span data-stu-id="93963-107">The ChangeFeedEventHost is shutting down.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Unknown">
      <MemberSignature Language="C#" Value="Unknown" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverCloseReason Unknown = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverCloseReason.Unknown" />
      <MemberSignature Language="VB.NET" Value="Unknown" />
      <MemberSignature Language="F#" Value="Unknown = 0" Usage="Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverCloseReason.Unknown" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverCloseReason</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="93963-108">Unbekannter Fehler.</span><span class="sxs-lookup"><span data-stu-id="93963-108">Unknown failure.</span></span> <span data-ttu-id="93963-109">Dies sollte nie an die Beobachter gesendet werden.</span><span class="sxs-lookup"><span data-stu-id="93963-109">This should never be sent to observers.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>