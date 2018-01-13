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
            Enthält die Erweiterungsmethoden, die im Zusammenhang mit Akteur-Ereignissen.
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
        <typeparam name="TEvent">Der Typ der Ereignisschnittstelle.</typeparam>
        <param name="actorProxy">Der Akteur, der das Ereignis veröffentlicht wird.</param>
        <param name="subscriber">Der Abonnent, der die Ereignisse empfängt.</param>
        <summary>
            Abonnieren Sie eine veröffentlichte Akteur-Ereignis aus.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Vorgang des Abonnieren einer veröffentlichten Akteur Ereignisses darstellt.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <para>Wenn ActorProxy ist nicht vom Typ <see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxy" /> </para>.
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
        <typeparam name="TEvent">Der Typ der Ereignisschnittstelle.</typeparam>
        <param name="actorProxy">Der Akteur, der das Ereignis veröffentlicht wird.</param>
        <param name="subscriber">Der Abonnent, der die Ereignisse empfängt.</param>
        <param name="resubscriptionInterval">Die Zeit zwischen Abonnements erneute Versuche.</param>
        <summary>
            Abonnieren Sie eine veröffentlichte Akteur-Ereignis aus.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Vorgang des Abonnieren einer veröffentlichten Akteur Ereignisses darstellt.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <para>Wenn ActorProxy ist nicht vom Typ <see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxy" /> </para>.
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
        <typeparam name="TEvent">Der Typ der Ereignisschnittstelle.</typeparam>
        <param name="actorProxy">Der Akteur, der das Ereignis veröffentlicht wird.</param>
        <param name="subscriber">Der Abonnent, der das Ereignis empfängt.</param>
        <summary>
            Kündigen Sie ein veröffentlichtes Akteur-Ereignis aus.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Vorgang des stellt nicht aus einem veröffentlichten Akteur Ereignis abonnieren.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <para>Wenn ActorProxy ist nicht vom Typ <see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxy" /> </para>.
            <para>Wenn keine TEvent implementieren.<see cref="T:Microsoft.ServiceFabric.Actors.IActorEvents" /></para></exception>
      </Docs>
    </Member>
  </Members>
</Type>