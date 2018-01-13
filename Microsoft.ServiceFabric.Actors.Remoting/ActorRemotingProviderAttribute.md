<Type Name="ActorRemotingProviderAttribute" FullName="Microsoft.ServiceFabric.Actors.Remoting.ActorRemotingProviderAttribute">
  <TypeSignature Language="C#" Value="public abstract class ActorRemotingProviderAttribute : Attribute" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ActorRemotingProviderAttribute extends System.Attribute" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Remoting.ActorRemotingProviderAttribute" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ActorRemotingProviderAttribute&#xA;Inherits Attribute" />
  <TypeSignature Language="F#" Value="type ActorRemotingProviderAttribute = class&#xA;    inherit Attribute" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Attribute</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.AttributeUsage(System.AttributeTargets.Assembly)</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Dies ist ein Basistyp für das Attribut, das festlegt Remoting Standardanbieter für das Remoting zu verwenden, die Akteur-Schnittstellen definiert, oder in der Assembly verwendet.
            </summary>
    <remarks>
      <para>
                Auf Dienstseite-Implementierung des Attributs gesucht wird durch <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorService" /> an Standardeinstellung erstellen <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> dafür. 
                </para>
      <para>
                Auf Clientseite-Implementierung des Attributs gesucht wird durch <see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" /> Konstruktor zum Erstellen eines standardmäßigen <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" /> wenn er nicht angegeben wird.
                </para>
      <para>
                Beachten Sie, die auf Client side Wenn Akteur Proxy erstellt wird, mithilfe der statischen <see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxy" /> -Klasse, verwendet den Standardwert <see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" /> einmal und daher die Anbieter-Suche erfolgt, nur zum ersten Mal in einer Assembly, wonach die gleiche Anbieter verwendet wird.
                </para>
      <para>
                Dieses Attribut ist in der folgenden Reihenfolge gesucht: <list type="number"> <item> im Eintrag <see cref="T:System.Reflection.Assembly" /> durch Aufrufen der Methode abgerufenen <see cref="M:System.Reflection.Assembly.GetEntryAssembly" /> </item> <item> In der <see cref="T:System.Reflection.Assembly" /> , definiert der remote-Schnittstelle für die Listener oder Proxy wird erstellt.</item></list></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ActorRemotingProviderAttribute ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.ActorRemotingProviderAttribute.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
                Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceFabric.Actors.Remoting.ActorRemotingProviderAttribute" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingClientFactory">
      <MemberSignature Language="C#" Value="public abstract Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactory (Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient callbackClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactory(class Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient callbackClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.ActorRemotingProviderAttribute.CreateServiceRemotingClientFactory(Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CreateServiceRemotingClientFactory (callbackClient As IServiceRemotingCallbackClient) As IServiceRemotingClientFactory" />
      <MemberSignature Language="F#" Value="abstract member CreateServiceRemotingClientFactory : Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient -&gt; Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" Usage="actorRemotingProviderAttribute.CreateServiceRemotingClientFactory callbackClient" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callbackClient" Type="Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient" />
      </Parameters>
      <Docs>
        <param name="callbackClient">
                Die Clientimplementierung, in denen die Rückrufe weitergeleitet werden soll.
            </param>
        <summary>
                Erstellt eine Verbindung zu den Schnittstellen prozessübergreifendes Akteur als Remoting-Client eine Dienstzuordnungsinstanz an.
            </summary>
        <returns>
                Ein <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" /> , die verwendet werden kann, mit <see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" /> um Akteur Proxy mit dem Akteur über Remote Akteur Schnittstelle sprechen zu generieren.
                </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingClientFactoryV2">
      <MemberSignature Language="C#" Value="public abstract Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactoryV2 (Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler callbackMessageHandler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactoryV2(class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler callbackMessageHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.ActorRemotingProviderAttribute.CreateServiceRemotingClientFactoryV2(Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CreateServiceRemotingClientFactoryV2 (callbackMessageHandler As IServiceRemotingCallbackMessageHandler) As IServiceRemotingClientFactory" />
      <MemberSignature Language="F#" Value="abstract member CreateServiceRemotingClientFactoryV2 : Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory" Usage="actorRemotingProviderAttribute.CreateServiceRemotingClientFactoryV2 callbackMessageHandler" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callbackMessageHandler" Type="Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler" />
      </Parameters>
      <Docs>
        <param name="callbackMessageHandler">Die Clientimplementierung, in denen die Rückrufe weitergeleitet werden soll.</param>
        <summary>
            Erstellt eine Dienst-Remoting-Client-Factory, die verwendet werden kann die <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.ServiceProxyFactory" /> um einen Proxy für die Remoteschnittstelle des Diensts zu erstellen.
            </summary>
        <returns><see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingListener">
      <MemberSignature Language="C#" Value="public abstract Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListener (Microsoft.ServiceFabric.Actors.Runtime.ActorService actorService);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListener(class Microsoft.ServiceFabric.Actors.Runtime.ActorService actorService) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.ActorRemotingProviderAttribute.CreateServiceRemotingListener(Microsoft.ServiceFabric.Actors.Runtime.ActorService)" />
      <MemberSignature Language="F#" Value="abstract member CreateServiceRemotingListener : Microsoft.ServiceFabric.Actors.Runtime.ActorService -&gt; Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" Usage="actorRemotingProviderAttribute.CreateServiceRemotingListener actorService" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorService" Type="Microsoft.ServiceFabric.Actors.Runtime.ActorService" />
      </Parameters>
      <Docs>
        <param name="actorService">
                Die Implementierung der Akteur-Dienst, der die Akteure hostet, deren Schnittstellen Remote ausgeführt werden muss.
                </param>
        <summary>
                Erstellt einen Dienst Remoting-Listener für das Remoting die Akteur-Schnittstellen.
            </summary>
        <returns>
                Ein <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> für den angegebenen Akteur-Dienst.
                </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingListenerV2">
      <MemberSignature Language="C#" Value="public abstract Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListenerV2 (Microsoft.ServiceFabric.Actors.Runtime.ActorService actorService);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListenerV2(class Microsoft.ServiceFabric.Actors.Runtime.ActorService actorService) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.ActorRemotingProviderAttribute.CreateServiceRemotingListenerV2(Microsoft.ServiceFabric.Actors.Runtime.ActorService)" />
      <MemberSignature Language="F#" Value="abstract member CreateServiceRemotingListenerV2 : Microsoft.ServiceFabric.Actors.Runtime.ActorService -&gt; Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" Usage="actorRemotingProviderAttribute.CreateServiceRemotingListenerV2 actorService" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorService" Type="Microsoft.ServiceFabric.Actors.Runtime.ActorService" />
      </Parameters>
      <Docs>
        <param name="actorService">
                Die Implementierung der Akteur-Dienst, der die Akteure hostet, deren Schnittstellen Remote ausgeführt werden muss.
                </param>
        <summary>
            Erstellt einen V2 Dienst Remoting-Listener für das Remoting Dienstschnittstelle.
            </summary>
        <returns>Ein <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> für den angegebenen Dienst.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemotingClient">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Services.Remoting.RemotingClient RemotingClient { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceFabric.Services.Remoting.RemotingClient RemotingClient" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Remoting.ActorRemotingProviderAttribute.RemotingClient" />
      <MemberSignature Language="VB.NET" Value="Public Property RemotingClient As RemotingClient" />
      <MemberSignature Language="F#" Value="member this.RemotingClient : Microsoft.ServiceFabric.Services.Remoting.RemotingClient with get, set" Usage="Microsoft.ServiceFabric.Actors.Remoting.ActorRemotingProviderAttribute.RemotingClient" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.RemotingClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            RemotingClient wird verwendet, um zu bestimmen, wo V1 oder V2 Remoting Client verwendet wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemotingListener">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Services.Remoting.RemotingListener RemotingListener { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceFabric.Services.Remoting.RemotingListener RemotingListener" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Remoting.ActorRemotingProviderAttribute.RemotingListener" />
      <MemberSignature Language="VB.NET" Value="Public Property RemotingListener As RemotingListener" />
      <MemberSignature Language="F#" Value="member this.RemotingListener : Microsoft.ServiceFabric.Services.Remoting.RemotingListener with get, set" Usage="Microsoft.ServiceFabric.Actors.Remoting.ActorRemotingProviderAttribute.RemotingListener" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.RemotingListener</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            RemotingListener wird verwendet, um zu bestimmen, auf dem Listener in V1, V2 oder Komprimierungsmodus ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>