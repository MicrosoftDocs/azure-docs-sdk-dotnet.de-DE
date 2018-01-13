<Type Name="ActorServiceRemotingDispatcher" FullName="Microsoft.ServiceFabric.Actors.Remoting.V2.Runtime.ActorServiceRemotingDispatcher">
  <TypeSignature Language="C#" Value="public class ActorServiceRemotingDispatcher : Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.ServiceRemotingMessageDispatcher" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ActorServiceRemotingDispatcher extends Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.ServiceRemotingMessageDispatcher" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Remoting.V2.Runtime.ActorServiceRemotingDispatcher" />
  <TypeSignature Language="VB.NET" Value="Public Class ActorServiceRemotingDispatcher&#xA;Inherits ServiceRemotingMessageDispatcher" />
  <TypeSignature Language="F#" Value="type ActorServiceRemotingDispatcher = class&#xA;    inherit ServiceRemotingMessageDispatcher" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.ServiceRemotingMessageDispatcher</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt eine Implementierung von <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler" /> können, die dispatch-Nachrichten mit einem Akteur-Dienst und den Akteuren, die in der Dienst gehostet.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActorServiceRemotingDispatcher (Microsoft.ServiceFabric.Actors.Runtime.ActorService actorService, Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory serviceRemotingRequestMessageBodyFactory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceFabric.Actors.Runtime.ActorService actorService, class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory serviceRemotingRequestMessageBodyFactory) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.V2.Runtime.ActorServiceRemotingDispatcher.#ctor(Microsoft.ServiceFabric.Actors.Runtime.ActorService,Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.Remoting.V2.Runtime.ActorServiceRemotingDispatcher : Microsoft.ServiceFabric.Actors.Runtime.ActorService * Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory -&gt; Microsoft.ServiceFabric.Actors.Remoting.V2.Runtime.ActorServiceRemotingDispatcher" Usage="new Microsoft.ServiceFabric.Actors.Remoting.V2.Runtime.ActorServiceRemotingDispatcher (actorService, serviceRemotingRequestMessageBodyFactory)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="actorService" Type="Microsoft.ServiceFabric.Actors.Runtime.ActorService" />
        <Parameter Name="serviceRemotingRequestMessageBodyFactory" Type="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory" />
      </Parameters>
      <Docs>
        <param name="actorService">Ein Akteur-Dienstinstanz.</param>
        <param name="serviceRemotingRequestMessageBodyFactory"></param>
        <summary>
            Instanziiert die ActorServiceRemotingDispatcher, die Nachrichten mit einem Akteur-Dienst und den Akteuren, die in der Dienst gehostet weitergeleitet werden kann...
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HandleRequestResponseAsync">
      <MemberSignature Language="C#" Value="public override System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessage&gt; HandleRequestResponseAsync (Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingRequestContext requestContext, Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessage requestMessage);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessage&gt; HandleRequestResponseAsync(class Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingRequestContext requestContext, class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessage requestMessage) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.V2.Runtime.ActorServiceRemotingDispatcher.HandleRequestResponseAsync(Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingRequestContext,Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessage)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function HandleRequestResponseAsync (requestContext As IServiceRemotingRequestContext, requestMessage As IServiceRemotingRequestMessage) As Task(Of IServiceRemotingResponseMessage)" />
      <MemberSignature Language="F#" Value="override this.HandleRequestResponseAsync : Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingRequestContext * Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessage -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessage&gt;" Usage="actorServiceRemotingDispatcher.HandleRequestResponseAsync (requestContext, requestMessage)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestContext" Type="Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingRequestContext" />
        <Parameter Name="requestMessage" Type="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessage" />
      </Parameters>
      <Docs>
        <param name="requestContext">-Anforderungskontext, die ermöglicht, den Rückrufkanal abrufen, falls erforderlich.</param>
        <param name="requestMessage">Remoting-Meldung.</param>
        <summary>
            Sendet die Nachrichten an die Webdienstmethoden Akteur oder der Akteur Methoden vom Client empfangen.
            Dies kann durch Benutzer verwendet werden, in dem wissen sie InterfaceId "und" MethodId für die Methode, um die Verteilung erfolgen.
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HandleRequestResponseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody&gt; HandleRequestResponseAsync (Microsoft.ServiceFabric.Actors.Remoting.V2.ActorRemotingDispatchHeaders actorDispatchHeaders, Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody requestBody, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody&gt; HandleRequestResponseAsync(class Microsoft.ServiceFabric.Actors.Remoting.V2.ActorRemotingDispatchHeaders actorDispatchHeaders, class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody requestBody, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.V2.Runtime.ActorServiceRemotingDispatcher.HandleRequestResponseAsync(Microsoft.ServiceFabric.Actors.Remoting.V2.ActorRemotingDispatchHeaders,Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="override this.HandleRequestResponseAsync : Microsoft.ServiceFabric.Actors.Remoting.V2.ActorRemotingDispatchHeaders * Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody&gt;" Usage="actorServiceRemotingDispatcher.HandleRequestResponseAsync (actorDispatchHeaders, requestBody, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorDispatchHeaders" Type="Microsoft.ServiceFabric.Actors.Remoting.V2.ActorRemotingDispatchHeaders" />
        <Parameter Name="requestBody" Type="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="actorDispatchHeaders"></param>
        <param name="requestBody"></param>
        <param name="cancellationToken"></param>
        <summary>
            Sendet die Nachrichten an die Webdienstmethoden Akteur oder der Akteur Methoden vom Client empfangen.
            Dies ist möglich, die vom Benutzer als eine unabhängige Verteiler wie die verkürzte verwendet werden.
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>