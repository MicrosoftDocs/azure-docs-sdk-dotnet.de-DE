<Type Name="WcfCommunicationListener&lt;TServiceContract&gt;" FullName="Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener&lt;TServiceContract&gt;">
  <TypeSignature Language="C#" Value="public class WcfCommunicationListener&lt;TServiceContract&gt; : Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WcfCommunicationListener`1&lt;TServiceContract&gt; extends System.Object implements class Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener`1" />
  <TypeSignature Language="VB.NET" Value="Public Class WcfCommunicationListener(Of TServiceContract)&#xA;Implements ICommunicationListener" />
  <TypeSignature Language="F#" Value="type WcfCommunicationListener&lt;'ServiceContract&gt; = class&#xA;    interface ICommunicationListener" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TServiceContract" />
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="TServiceContract">Der Typ des WCF-Dienstvertrags.</typeparam>
    <summary>
            Windows Communication Foundation-basierten Listener für Service Fabric basierend zustandslose oder zustandsbehaftete Dienst.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WcfCommunicationListener (System.Fabric.ServiceContext serviceContext, TServiceContract wcfServiceObject);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, !TServiceContract wcfServiceObject) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener`1.#ctor(System.Fabric.ServiceContext,`0)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener&lt;'ServiceContract&gt; : System.Fabric.ServiceContext * 'ServiceContract -&gt; Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener&lt;'ServiceContract&gt;" Usage="new Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener&lt;'ServiceContract&gt; (serviceContext, wcfServiceObject)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="wcfServiceObject" Type="TServiceContract" />
      </Parameters>
      <Docs>
        <param name="serviceContext">
                Der Kontext des Diensts für die Kommunikation Listener erstellt wird.
            </param>
        <param name="wcfServiceObject">
                WCF-Dienst den angegebenen WCF-Dienstvertrag implementieren.
            </param>
        <summary>
                Ein WCF-Konstrukte basierend Kommunikation Listener, die standardmäßige Bindung und Endpunktadresse standardmäßig verwendet.
            </summary>
        <remarks>
          <para>
                    Der Standardlistener, die Bindung wird mit erstellt <see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpListenerBinding(System.Int64,System.TimeSpan,System.TimeSpan)" /> Methode.
                </para>
          <para>
                    Die Standardadresse für den Endpunkt wird erstellt, mit der Endpoint-Ressource, die in das Manifest definiert. Der Name der endpunktressource stammt aus der WCF-Diensts Vertrag Typ mithilfe <see cref="M:Microsoft.ServiceFabric.Services.ServiceNameFormat.GetEndpointName(System.Type)" /> Methode.
                    Wenn übereinstimmende Endpoint-Ressource nicht in das Manifest gefunden wird, wird eine standardmäßige Ressource Endpunktdefinition mit Port 0 (null) verwendet.
                    </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WcfCommunicationListener (System.Fabric.ServiceContext serviceContext, TServiceContract wcfServiceObject, System.ServiceModel.Channels.Binding listenerBinding = null, System.ServiceModel.EndpointAddress address = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, !TServiceContract wcfServiceObject, class System.ServiceModel.Channels.Binding listenerBinding, class System.ServiceModel.EndpointAddress address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener`1.#ctor(System.Fabric.ServiceContext,`0,System.ServiceModel.Channels.Binding,System.ServiceModel.EndpointAddress)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener&lt;'ServiceContract&gt; : System.Fabric.ServiceContext * 'ServiceContract * System.ServiceModel.Channels.Binding * System.ServiceModel.EndpointAddress -&gt; Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener&lt;'ServiceContract&gt;" Usage="new Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener&lt;'ServiceContract&gt; (serviceContext, wcfServiceObject, listenerBinding, address)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="wcfServiceObject" Type="TServiceContract" />
        <Parameter Name="listenerBinding" Type="System.ServiceModel.Channels.Binding" />
        <Parameter Name="address" Type="System.ServiceModel.EndpointAddress" />
      </Parameters>
      <Docs>
        <param name="serviceContext">
                Der Kontext des Diensts für die Kommunikation Listener erstellt wird.
            </param>
        <param name="wcfServiceObject">
                WCF-Dienst den angegebenen WCF-Dienstvertrag implementieren.
            </param>
        <param name="listenerBinding">
                Die Bindung, die für den WCF-Endpunkt verwendet werden soll. Wenn die ListenerBinding nicht angegeben ist, oder es null ist, ein Standardlistener, der Bindung ist mit erstellt <see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpListenerBinding(System.Int64,System.TimeSpan,System.TimeSpan)" /> Methode.
                </param>
        <param name="address">
                Die abhöradresse für den WCF-Endpunkt. Wenn die Adresse nicht angegeben ist, oder es null ist, wird eine Standardadresse durch die Suche nach Endpoint-Ressource aus dem Dienstmanifest erstellt. Der Ressourcenname Endpunkt stammt aus der WCF-Diensts Vertrag Typ mithilfe <see cref="M:Microsoft.ServiceFabric.Services.ServiceNameFormat.GetEndpointName(System.Type)" /> Methode.
                Wenn übereinstimmende Endpoint-Ressource nicht in das Manifest gefunden wird, wird eine standardmäßige Ressource Endpunktdefinition mit Port 0 (null) verwendet.
                </param>
        <summary>
                Ein WCF-Konstrukte basierend Kommunikation Listener, den angegebenen Listener, die Bindung und Endpunktadresse, die von der angegebenen Endpunktadresse abgeleitet wird.
                </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WcfCommunicationListener (System.Fabric.ServiceContext serviceContext, TServiceContract wcfServiceObject, System.ServiceModel.Channels.Binding listenerBinding = null, string endpointResourceName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, !TServiceContract wcfServiceObject, class System.ServiceModel.Channels.Binding listenerBinding, string endpointResourceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener`1.#ctor(System.Fabric.ServiceContext,`0,System.ServiceModel.Channels.Binding,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener&lt;'ServiceContract&gt; : System.Fabric.ServiceContext * 'ServiceContract * System.ServiceModel.Channels.Binding * string -&gt; Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener&lt;'ServiceContract&gt;" Usage="new Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener&lt;'ServiceContract&gt; (serviceContext, wcfServiceObject, listenerBinding, endpointResourceName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="wcfServiceObject" Type="TServiceContract" />
        <Parameter Name="listenerBinding" Type="System.ServiceModel.Channels.Binding" />
        <Parameter Name="endpointResourceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceContext">
                Der Kontext des Diensts für die Kommunikation Listener erstellt wird.
            </param>
        <param name="wcfServiceObject">
                WCF-Dienst den angegebenen WCF-Dienstvertrag implementieren.
            </param>
        <param name="listenerBinding">
                Die Bindung, die für den WCF-Endpunkt verwendet werden soll. Wenn die ListenerBinding nicht angegeben ist, oder es null ist, ein Standardlistener, der Bindung ist mit erstellt <see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpListenerBinding(System.Int64,System.TimeSpan,System.TimeSpan)" /> Methode.
                </param>
        <param name="endpointResourceName">
                Der Name der endpunktressource definiert, in das Manifest, das verwendet werden soll, um die Adresse für den Listener zu erstellen. Wenn die EndpointResourceName nicht angegeben ist, oder es null ist, wird der Name abgeleitet, von der WCF-Diensts Vertrag Typ mithilfe <see cref="M:Microsoft.ServiceFabric.Services.ServiceNameFormat.GetEndpointName(System.Type)" /> Methode.
                Wenn übereinstimmende Endpoint-Ressource nicht in das Manifest gefunden wird, wird eine standardmäßige Ressource Endpunktdefinition mit Port 0 (null) verwendet.
                </param>
        <summary>
                Ein WCF-Konstrukte basierend Kommunikation Listener, den angegebenen Listener, die Bindung und Endpunktadresse abgeleitet aus dem angegebenen Endpunktnamen Ressource verwendet.
                </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.Abort">
      <MemberSignature Language="C#" Value="void ICommunicationListener.Abort ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.Abort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener`1.Microsoft#ServiceFabric#Services#Communication#Runtime#ICommunicationListener#Abort" />
      <MemberSignature Language="VB.NET" Value="Sub Abort () Implements ICommunicationListener.Abort" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.Abort</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Diese Methode bewirkt, dass den Listener Kommunikation zu schließen. Schließen ist ein Endstatus und diese Methode bewirkt, dass des Übergangs nicht ordnungsgemäß geschlossen. Alle ausstehenden Vorgänge (einschließlich schließen) sollte abgebrochen werden, wenn diese Methode aufgerufen wird.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.CloseAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task ICommunicationListener.CloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.CloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener`1.Microsoft#ServiceFabric#Services#Communication#Runtime#ICommunicationListener#CloseAsync(System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.CloseAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener`1/&lt;Microsoft-ServiceFabric-Services-Communication-Runtime-ICommunicationListener-CloseAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">Abbruchtoken</param>
        <summary>
            Diese Methode bewirkt, dass den Listener Kommunikation zu schließen. Schließen ist ein Endstatus und diese Methode ermöglicht die Kommunikation-Listener für den Übergang in diesen Zustand auf ordnungsgemäße Weise.
            </summary>
        <returns>
            Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehenden Vorgang darstellt.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.OpenAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;string&gt; ICommunicationListener.OpenAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.OpenAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener`1.Microsoft#ServiceFabric#Services#Communication#Runtime#ICommunicationListener#OpenAsync(System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.OpenAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">Abbruchtoken</param>
        <summary>
            Diese Methode bewirkt, dass die Kommunikation Listener geöffnet werden. Nach Abschluss der öffnen, der Listener für die Kommunikation wird verwendbar - akzeptiert, und sendet Nachrichten ab.
            </summary>
        <returns>
            Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehenden Vorgang darstellt. Das Ergebnis der Aufgabe ist die Endpunktzeichenfolge.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceHost">
      <MemberSignature Language="C#" Value="public System.ServiceModel.ServiceHost ServiceHost { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.ServiceModel.ServiceHost ServiceHost" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener`1.ServiceHost" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceHost As ServiceHost" />
      <MemberSignature Language="F#" Value="member this.ServiceHost : System.ServiceModel.ServiceHost" Usage="Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener&lt;'ServiceContract&gt;.ServiceHost" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.ServiceHost</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
                Ruft die <see cref="T:System.ServiceModel.ServiceHost" /> , die zum Hosten von WCF-Dienst-Implementierung von diesem Listener verwendet.
                </summary>
        <value>
                Ein <see cref="T:System.ServiceModel.ServiceHost" /> , die zum Hosten von WCF-Dienst-Implementierung von diesem Listener verwendet.
                </value>
        <remarks>
                Der Diensthost wird vom Listener in seinem Konstruktor erstellt. Bevor Sie diese Kommunikation Listener geöffnet wird, von der Laufzeit über <see cref="M:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.OpenAsync(System.Threading.CancellationToken)" /> -Methode, der Diensthost durch den Zugriff auf ihn über diese Eigenschaft angepasst werden.
                </remarks>
      </Docs>
    </Member>
  </Members>
</Type>