<Type Name="ActorProxyEventExtensions" FullName="Microsoft.ServiceFabric.Actors.Client.ActorProxyEventExtensions">
  <TypeSignature Language="C#" Value="public static class ActorProxyEventExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ActorProxyEventExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Client.ActorProxyEventExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ActorProxyEventExtensions" />
  <TypeSignature Language="F#" Value="type ActorProxyEventExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="59f77-101">Enthält die Erweiterungsmethoden, die im Zusammenhang mit Akteur-Ereignissen.</span><span class="sxs-lookup"><span data-stu-id="59f77-101">Contains extension methods related to actor events.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="SubscribeAsync&lt;TEvent&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task SubscribeAsync&lt;TEvent&gt; (this Microsoft.ServiceFabric.Actors.IActorEventPublisher actorProxy, TEvent subscriber) where TEvent : Microsoft.ServiceFabric.Actors.IActorEvents;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task SubscribeAsync&lt;(class Microsoft.ServiceFabric.Actors.IActorEvents) TEvent&gt;(class Microsoft.ServiceFabric.Actors.IActorEventPublisher actorProxy, !!TEvent subscriber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorProxyEventExtensions.SubscribeAsync``1(Microsoft.ServiceFabric.Actors.IActorEventPublisher,``0)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SubscribeAsync(Of TEvent As IActorEvents) (actorProxy As IActorEventPublisher, subscriber As TEvent) As Task" />
      <MemberSignature Language="F#" Value="static member SubscribeAsync : Microsoft.ServiceFabric.Actors.IActorEventPublisher * 'Event -&gt; System.Threading.Tasks.Task (requires 'Event :&gt; Microsoft.ServiceFabric.Actors.IActorEvents)" Usage="Microsoft.ServiceFabric.Actors.Client.ActorProxyEventExtensions.SubscribeAsync (actorProxy, subscriber)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TEvent">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Actors.IActorEvents</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="actorProxy" Type="Microsoft.ServiceFabric.Actors.IActorEventPublisher" RefType="this" />
        <Parameter Name="subscriber" Type="TEvent" />
      </Parameters>
      <Docs>
        <typeparam name="TEvent"><span data-ttu-id="59f77-102">Der Typ der Ereignisschnittstelle.</span><span class="sxs-lookup"><span data-stu-id="59f77-102">The type of the event interface.</span></span></typeparam>
        <param name="actorProxy"><span data-ttu-id="59f77-103">Der Akteur, der das Ereignis veröffentlicht wird.</span><span class="sxs-lookup"><span data-stu-id="59f77-103">The actor that publishes the event.</span></span></param>
        <param name="subscriber"><span data-ttu-id="59f77-104">Der Abonnent, der die Ereignisse empfängt.</span><span class="sxs-lookup"><span data-stu-id="59f77-104">The subscriber that receives the events.</span></span></param>
        <summary>
            <span data-ttu-id="59f77-105">Abonnieren Sie eine veröffentlichte Akteur-Ereignis aus.</span><span class="sxs-lookup"><span data-stu-id="59f77-105">Subscribe to a published actor event.</span></span>
            </summary>
        <returns><span data-ttu-id="59f77-106">Eine Aufgabe, die den asynchronen Vorgang des Abonnieren einer veröffentlichten Akteur Ereignisses darstellt.</span><span class="sxs-lookup"><span data-stu-id="59f77-106">A task that represents the asynchronous operation of subscribing to a published actor event.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="59f77-107"><para>Wenn ActorProxy ist nicht vom Typ <see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxy" /> </para>.</span><span class="sxs-lookup"><span data-stu-id="59f77-107"><para>When actorProxy is not of type <see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxy" /></para>.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="SubscribeAsync&lt;TEvent&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task SubscribeAsync&lt;TEvent&gt; (this Microsoft.ServiceFabric.Actors.IActorEventPublisher actorProxy, TEvent subscriber, TimeSpan resubscriptionInterval) where TEvent : Microsoft.ServiceFabric.Actors.IActorEvents;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task SubscribeAsync&lt;(class Microsoft.ServiceFabric.Actors.IActorEvents) TEvent&gt;(class Microsoft.ServiceFabric.Actors.IActorEventPublisher actorProxy, !!TEvent subscriber, valuetype System.TimeSpan resubscriptionInterval) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorProxyEventExtensions.SubscribeAsync``1(Microsoft.ServiceFabric.Actors.IActorEventPublisher,``0,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SubscribeAsync(Of TEvent As IActorEvents) (actorProxy As IActorEventPublisher, subscriber As TEvent, resubscriptionInterval As TimeSpan) As Task" />
      <MemberSignature Language="F#" Value="static member SubscribeAsync : Microsoft.ServiceFabric.Actors.IActorEventPublisher * 'Event * TimeSpan -&gt; System.Threading.Tasks.Task (requires 'Event :&gt; Microsoft.ServiceFabric.Actors.IActorEvents)" Usage="Microsoft.ServiceFabric.Actors.Client.ActorProxyEventExtensions.SubscribeAsync (actorProxy, subscriber, resubscriptionInterval)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Actors.Client.ActorProxyEventExtensions/&lt;SubscribeAsync&gt;d__2`1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TEvent">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Actors.IActorEvents</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="actorProxy" Type="Microsoft.ServiceFabric.Actors.IActorEventPublisher" RefType="this" />
        <Parameter Name="subscriber" Type="TEvent" />
        <Parameter Name="resubscriptionInterval" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <typeparam name="TEvent"><span data-ttu-id="59f77-108">Der Typ der Ereignisschnittstelle.</span><span class="sxs-lookup"><span data-stu-id="59f77-108">The type of the event interface.</span></span></typeparam>
        <param name="actorProxy"><span data-ttu-id="59f77-109">Der Akteur, der das Ereignis veröffentlicht wird.</span><span class="sxs-lookup"><span data-stu-id="59f77-109">The actor that publishes the event.</span></span></param>
        <param name="subscriber"><span data-ttu-id="59f77-110">Der Abonnent, der die Ereignisse empfängt.</span><span class="sxs-lookup"><span data-stu-id="59f77-110">The subscriber that receives the events.</span></span></param>
        <param name="resubscriptionInterval"><span data-ttu-id="59f77-111">Die Zeit zwischen Abonnements erneute Versuche.</span><span class="sxs-lookup"><span data-stu-id="59f77-111">The time between re-subscription attempts.</span></span></param>
        <summary>
            <span data-ttu-id="59f77-112">Abonnieren Sie eine veröffentlichte Akteur-Ereignis aus.</span><span class="sxs-lookup"><span data-stu-id="59f77-112">Subscribe to a published actor event.</span></span>
            </summary>
        <returns><span data-ttu-id="59f77-113">Eine Aufgabe, die den asynchronen Vorgang des Abonnieren einer veröffentlichten Akteur Ereignisses darstellt.</span><span class="sxs-lookup"><span data-stu-id="59f77-113">A task that represents the asynchronous operation of subscribing to a published actor event.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="59f77-114"><para>Wenn ActorProxy ist nicht vom Typ <see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxy" /> </para>.</span><span class="sxs-lookup"><span data-stu-id="59f77-114"><para>When actorProxy is not of type <see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxy" /></para>.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UnsubscribeAsync&lt;TEvent&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UnsubscribeAsync&lt;TEvent&gt; (this Microsoft.ServiceFabric.Actors.IActorEventPublisher actorProxy, TEvent subscriber);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UnsubscribeAsync&lt;TEvent&gt;(class Microsoft.ServiceFabric.Actors.IActorEventPublisher actorProxy, !!TEvent subscriber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorProxyEventExtensions.UnsubscribeAsync``1(Microsoft.ServiceFabric.Actors.IActorEventPublisher,``0)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UnsubscribeAsync(Of TEvent) (actorProxy As IActorEventPublisher, subscriber As TEvent) As Task" />
      <MemberSignature Language="F#" Value="static member UnsubscribeAsync : Microsoft.ServiceFabric.Actors.IActorEventPublisher * 'Event -&gt; System.Threading.Tasks.Task" Usage="Microsoft.ServiceFabric.Actors.Client.ActorProxyEventExtensions.UnsubscribeAsync (actorProxy, subscriber)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TEvent" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="actorProxy" Type="Microsoft.ServiceFabric.Actors.IActorEventPublisher" RefType="this" />
        <Parameter Name="subscriber" Type="TEvent" />
      </Parameters>
      <Docs>
        <typeparam name="TEvent"><span data-ttu-id="59f77-115">Der Typ der Ereignisschnittstelle.</span><span class="sxs-lookup"><span data-stu-id="59f77-115">The type of the event interface.</span></span></typeparam>
        <param name="actorProxy"><span data-ttu-id="59f77-116">Der Akteur, der das Ereignis veröffentlicht wird.</span><span class="sxs-lookup"><span data-stu-id="59f77-116">The actor that publishes the event.</span></span></param>
        <param name="subscriber"><span data-ttu-id="59f77-117">Der Abonnent, der das Ereignis empfängt.</span><span class="sxs-lookup"><span data-stu-id="59f77-117">The subscriber that receives the event.</span></span></param>
        <summary>
            <span data-ttu-id="59f77-118">Kündigen Sie ein veröffentlichtes Akteur-Ereignis aus.</span><span class="sxs-lookup"><span data-stu-id="59f77-118">Unsubscribe from a published actor event.</span></span>
            </summary>
        <returns><span data-ttu-id="59f77-119">Eine Aufgabe, die den asynchronen Vorgang des stellt nicht aus einem veröffentlichten Akteur Ereignis abonnieren.</span><span class="sxs-lookup"><span data-stu-id="59f77-119">A task that represents the asynchronous operation of un-subscribing from a published actor event.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="59f77-120"><para>Wenn ActorProxy ist nicht vom Typ <see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxy" /> </para>.</span><span class="sxs-lookup"><span data-stu-id="59f77-120"><para>When actorProxy is not of type <see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxy" /></para>.</span></span>
            <span data-ttu-id="59f77-121"><para>Wenn keine TEvent implementieren.<see cref="T:Microsoft.ServiceFabric.Actors.IActorEvents" /></para></span><span class="sxs-lookup"><span data-stu-id="59f77-121"><para>When TEvent doesn't implement <see cref="T:Microsoft.ServiceFabric.Actors.IActorEvents" /></para></span></span></exception>
      </Docs>
    </Member>
  </Members>
</Type>