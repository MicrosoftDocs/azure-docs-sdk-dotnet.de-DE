<Type Name="WcfCommunicationClientFactory&lt;TServiceContract&gt;" FullName="Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClientFactory&lt;TServiceContract&gt;">
  <TypeSignature Language="C#" Value="public class WcfCommunicationClientFactory&lt;TServiceContract&gt; : Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase&lt;Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient&lt;TServiceContract&gt;&gt; where TServiceContract : class" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WcfCommunicationClientFactory`1&lt;class TServiceContract&gt; extends Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1&lt;class Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient`1&lt;!TServiceContract&gt;&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClientFactory`1" />
  <TypeSignature Language="VB.NET" Value="Public Class WcfCommunicationClientFactory(Of TServiceContract)&#xA;Inherits CommunicationClientFactoryBase(Of WcfCommunicationClient(Of TServiceContract))" />
  <TypeSignature Language="F#" Value="type WcfCommunicationClientFactory&lt;'ServiceContract (requires 'ServiceContract : null)&gt; = class&#xA;    inherit CommunicationClientFactoryBase&lt;WcfCommunicationClient&lt;'ServiceContract&gt;&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TServiceContract">
      <Constraints>
        <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase&lt;Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient&lt;TServiceContract&gt;&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient&lt;TServiceContract&gt;</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <typeparam name="TServiceContract">Basierten WCF-Dienstvertrags</typeparam>
    <summary>
            Ein <see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1" /> , die Windows Communication Foundation verwendet, erstellen Sie <see cref="T:Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient`1" /> für die Kommunikation mit zustandslosen und zustandsbehafteten Diensten, mit dem <see cref="T:Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener`1" />.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WcfCommunicationClientFactory (System.ServiceModel.Channels.Binding clientBinding = null, System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt; exceptionHandlers = null, Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver servicePartitionResolver = null, string traceId = null, object callback = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.ServiceModel.Channels.Binding clientBinding, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt; exceptionHandlers, class Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver servicePartitionResolver, string traceId, object callback) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClientFactory`1.#ctor(System.ServiceModel.Channels.Binding,System.Collections.Generic.IEnumerable{Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler},Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver,System.String,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional clientBinding As Binding = null, Optional exceptionHandlers As IEnumerable(Of IExceptionHandler) = null, Optional servicePartitionResolver As IServicePartitionResolver = null, Optional traceId As String = null, Optional callback As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClientFactory&lt;'ServiceContract (requires 'ServiceContract : null)&gt; : System.ServiceModel.Channels.Binding * seq&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt; * Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver * string * obj -&gt; Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClientFactory&lt;'ServiceContract (requires 'ServiceContract : null)&gt;" Usage="new Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClientFactory&lt;'ServiceContract (requires 'ServiceContract : null)&gt; (clientBinding, exceptionHandlers, servicePartitionResolver, traceId, callback)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clientBinding" Type="System.ServiceModel.Channels.Binding" />
        <Parameter Name="exceptionHandlers" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt;" />
        <Parameter Name="servicePartitionResolver" Type="Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver" />
        <Parameter Name="traceId" Type="System.String" />
        <Parameter Name="callback" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="clientBinding">
                WCF-Bindung für den Client verwenden. Wenn die Client-Bindung nicht angegeben ist oder null, eine standardmäßige Clientbindung wird mithilfe der <see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpClientBinding(System.Int64,System.TimeSpan,System.TimeSpan)" /> Methode erstellt eine <see cref="T:System.ServiceModel.NetTcpBinding" /> ohne Sicherheit.
                </param>
        <param name="exceptionHandlers">
                Der Ausnahmehandler behandelt die Ausnahmen, die bei der Kommunikation mit dem Dienst aufgetreten.
            </param>
        <param name="servicePartitionResolver">
                Partition-Konfliktlöser auf die Dienst-Endpunkten zu beheben. Wenn nicht angegeben ist, ein Standarddienst-Konfliktlöser Partition zurückgegebenes <see cref="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.GetDefault" /> verwendet wird.
                </param>
        <param name="traceId">
                ID, bei der Diagnose ablaufverfolgungen dieser Komponente verwendet.
            </param>
        <param name="callback">
                Der Rückruf-Client, der die Rückrufe vom Dienst empfängt.
            </param>
        <summary>
            Erstellt eine Factory zum Erstellen von Clients mithilfe von WCF für die Kommunikation mit den Diensten.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AbortClient">
      <MemberSignature Language="C#" Value="protected override void AbortClient (Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient&lt;TServiceContract&gt; client);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void AbortClient(class Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient`1&lt;!TServiceContract&gt; client) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClientFactory`1.AbortClient(Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient{`0})" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub AbortClient (client As WcfCommunicationClient(Of TServiceContract))" />
      <MemberSignature Language="F#" Value="override this.AbortClient : Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient&lt;'ServiceContract (requires 'ServiceContract : null)&gt; -&gt; unit" Usage="wcfCommunicationClientFactory.AbortClient client" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient&lt;TServiceContract&gt;" />
      </Parameters>
      <Docs>
        <param name="client">Kommunikationsclient</param>
        <summary>
            Bricht die angegebene client
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateClientAsync">
      <MemberSignature Language="C#" Value="protected override System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient&lt;TServiceContract&gt;&gt; CreateClientAsync (string endpoint, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient`1&lt;!TServiceContract&gt;&gt; CreateClientAsync(string endpoint, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClientFactory`1.CreateClientAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="override this.CreateClientAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient&lt;'ServiceContract&gt;&gt;" Usage="wcfCommunicationClientFactory.CreateClientAsync (endpoint, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClientFactory`1/&lt;CreateClientAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient&lt;TServiceContract&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpoint" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="endpoint">Die Endpunktadresse, in dem vom Dienst überwacht wird</param>
        <param name="cancellationToken">Abbruchtoken</param>
        <summary>
            Erstellt einen Client Kommunikation für die angegebene Endpunktadresse.
            </summary>
        <returns>Die Kommunikation zwischen Client, der erstellt wurde</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateWcfCommunicationClient">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient&lt;TServiceContract&gt; CreateWcfCommunicationClient (TServiceContract channel);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient`1&lt;!TServiceContract&gt; CreateWcfCommunicationClient(!TServiceContract channel) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClientFactory`1.CreateWcfCommunicationClient(`0)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function CreateWcfCommunicationClient (channel As TServiceContract) As WcfCommunicationClient(Of TServiceContract)" />
      <MemberSignature Language="F#" Value="abstract member CreateWcfCommunicationClient : 'ServiceContract -&gt; Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient&lt;'ServiceContract (requires 'ServiceContract : null)&gt;&#xA;override this.CreateWcfCommunicationClient : 'ServiceContract -&gt; Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient&lt;'ServiceContract (requires 'ServiceContract : null)&gt;" Usage="wcfCommunicationClientFactory.CreateWcfCommunicationClient channel" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient&lt;TServiceContract&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="channel" Type="TServiceContract" />
      </Parameters>
      <Docs>
        <param name="channel">Dienstvertrag basierten WCF-Kanal.</param>
        <summary>
            Kommunikation zwischen WCF-Clients für die Kommunikation über den angegebenen Kanal wird erstellt.
            </summary>
        <returns>Die Kommunikation zwischen Client, der erstellt wurde</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateClient">
      <MemberSignature Language="C#" Value="protected override bool ValidateClient (Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient&lt;TServiceContract&gt; client);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool ValidateClient(class Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient`1&lt;!TServiceContract&gt; client) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClientFactory`1.ValidateClient(Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient{`0})" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function ValidateClient (client As WcfCommunicationClient(Of TServiceContract)) As Boolean" />
      <MemberSignature Language="F#" Value="override this.ValidateClient : Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient&lt;'ServiceContract (requires 'ServiceContract : null)&gt; -&gt; bool" Usage="wcfCommunicationClientFactory.ValidateClient client" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient&lt;TServiceContract&gt;" />
      </Parameters>
      <Docs>
        <param name="client">WCF-Kommunikation-client</param>
        <summary>
            Gibt "true" zurück, wenn der Client noch gültig ist. Dienstorientierte verbindungstransporte können diese Methode verwenden, um anzugeben, dass der Client nicht mehr mit dem Dienst verbunden ist.
            </summary>
        <returns>"true", wenn der Client gültig, andernfalls false ist</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateClient">
      <MemberSignature Language="C#" Value="protected override bool ValidateClient (string endpoint, Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient&lt;TServiceContract&gt; client);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool ValidateClient(string endpoint, class Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient`1&lt;!TServiceContract&gt; client) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClientFactory`1.ValidateClient(System.String,Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient{`0})" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function ValidateClient (endpoint As String, client As WcfCommunicationClient(Of TServiceContract)) As Boolean" />
      <MemberSignature Language="F#" Value="override this.ValidateClient : string * Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient&lt;'ServiceContract (requires 'ServiceContract : null)&gt; -&gt; bool" Usage="wcfCommunicationClientFactory.ValidateClient (endpoint, client)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpoint" Type="System.String" />
        <Parameter Name="client" Type="Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient&lt;TServiceContract&gt;" />
      </Parameters>
      <Docs>
        <param name="endpoint">Endpunktzeichenfolge</param>
        <param name="client">WCF-Kommunikation-client</param>
        <summary>
            Gibt true zurück, wenn der Client noch gültig und mit den im Parameter angegebenen Endpunkt verbunden ist.
            </summary>
        <returns>"true", wenn der Client gültig, andernfalls false ist</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>