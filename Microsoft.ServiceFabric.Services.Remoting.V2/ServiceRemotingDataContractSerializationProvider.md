<Type Name="ServiceRemotingDataContractSerializationProvider" FullName="Microsoft.ServiceFabric.Services.Remoting.V2.ServiceRemotingDataContractSerializationProvider">
  <TypeSignature Language="C#" Value="public class ServiceRemotingDataContractSerializationProvider : Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServiceRemotingDataContractSerializationProvider extends System.Object implements class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V2.ServiceRemotingDataContractSerializationProvider" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceRemotingDataContractSerializationProvider&#xA;Implements IServiceRemotingMessageSerializationProvider" />
  <TypeSignature Language="F#" Value="type ServiceRemotingDataContractSerializationProvider = class&#xA;    interface IServiceRemotingMessageSerializationProvider" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Dies ist die standardmäßige Implementierung für <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider" />von Remoting Dienst-als auch während der Anforderungs-/Antwort-Serialisierung verwendet. Es verwendet DataContract für die Serialisierung.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceRemotingDataContractSerializationProvider ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.ServiceRemotingDataContractSerializationProvider.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Erstellt eine ServiceRemotingDataContractSerializationProvider mit IBufferPoolManager 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceRemotingDataContractSerializationProvider (Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IBufferPoolManager bodyBufferPoolManager);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IBufferPoolManager bodyBufferPoolManager) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.ServiceRemotingDataContractSerializationProvider.#ctor(Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IBufferPoolManager)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (bodyBufferPoolManager As IBufferPoolManager)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.V2.ServiceRemotingDataContractSerializationProvider : Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IBufferPoolManager -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.ServiceRemotingDataContractSerializationProvider" Usage="new Microsoft.ServiceFabric.Services.Remoting.V2.ServiceRemotingDataContractSerializationProvider bodyBufferPoolManager" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="bodyBufferPoolManager" Type="Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IBufferPoolManager" />
      </Parameters>
      <Docs>
        <param name="bodyBufferPoolManager"></param>
        <summary>
            Erstellt eine ServiceRemotingDataContractSerializationProvider mit benutzerdefinierten IBufferPoolManager
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMessageBodyFactory">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory CreateMessageBodyFactory ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory CreateMessageBodyFactory() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.ServiceRemotingDataContractSerializationProvider.CreateMessageBodyFactory" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateMessageBodyFactory () As IServiceRemotingMessageBodyFactory" />
      <MemberSignature Language="F#" Value="abstract member CreateMessageBodyFactory : unit -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory&#xA;override this.CreateMessageBodyFactory : unit -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory" Usage="serviceRemotingDataContractSerializationProvider.CreateMessageBodyFactory " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider.CreateMessageBodyFactory</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Erstellt eine MessageFactory für DataContract Remoting-Servertypen. Dient zum Erstellen von Remoting Anforderung/Antwort-Objekten.
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateRequestMessageSerializer">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBodySerializer CreateRequestMessageSerializer (Type serviceInterfaceType, System.Collections.Generic.IEnumerable&lt;Type&gt; requestBodyTypes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBodySerializer CreateRequestMessageSerializer(class System.Type serviceInterfaceType, class System.Collections.Generic.IEnumerable`1&lt;class System.Type&gt; requestBodyTypes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.ServiceRemotingDataContractSerializationProvider.CreateRequestMessageSerializer(System.Type,System.Collections.Generic.IEnumerable{System.Type})" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateRequestMessageSerializer (serviceInterfaceType As Type, requestBodyTypes As IEnumerable(Of Type)) As IServiceRemotingRequestMessageBodySerializer" />
      <MemberSignature Language="F#" Value="abstract member CreateRequestMessageSerializer : Type * seq&lt;Type&gt; -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBodySerializer&#xA;override this.CreateRequestMessageSerializer : Type * seq&lt;Type&gt; -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBodySerializer" Usage="serviceRemotingDataContractSerializationProvider.CreateRequestMessageSerializer (serviceInterfaceType, requestBodyTypes)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider.CreateRequestMessageSerializer(System.Type,System.Collections.Generic.IEnumerable{System.Type})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBodySerializer</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceInterfaceType" Type="System.Type" />
        <Parameter Name="requestBodyTypes" Type="System.Collections.Generic.IEnumerable&lt;System.Type&gt;" />
      </Parameters>
      <Docs>
        <param name="serviceInterfaceType">Dienst-Benutzeroberfläche</param>
        <param name="requestBodyTypes">Parameter für alle Methoden in der serviceInterfaceType</param>
        <summary>
            Erstellt eine IServiceRemotingRequestMessageBodySerializer für eine ServiceInterface mit DataContract-Implementierung
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateResponseMessageSerializer">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBodySerializer CreateResponseMessageSerializer (Type serviceInterfaceType, System.Collections.Generic.IEnumerable&lt;Type&gt; responseBodyTypes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBodySerializer CreateResponseMessageSerializer(class System.Type serviceInterfaceType, class System.Collections.Generic.IEnumerable`1&lt;class System.Type&gt; responseBodyTypes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.ServiceRemotingDataContractSerializationProvider.CreateResponseMessageSerializer(System.Type,System.Collections.Generic.IEnumerable{System.Type})" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateResponseMessageSerializer (serviceInterfaceType As Type, responseBodyTypes As IEnumerable(Of Type)) As IServiceRemotingResponseMessageBodySerializer" />
      <MemberSignature Language="F#" Value="abstract member CreateResponseMessageSerializer : Type * seq&lt;Type&gt; -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBodySerializer&#xA;override this.CreateResponseMessageSerializer : Type * seq&lt;Type&gt; -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBodySerializer" Usage="serviceRemotingDataContractSerializationProvider.CreateResponseMessageSerializer (serviceInterfaceType, responseBodyTypes)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider.CreateResponseMessageSerializer(System.Type,System.Collections.Generic.IEnumerable{System.Type})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBodySerializer</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceInterfaceType" Type="System.Type" />
        <Parameter Name="responseBodyTypes" Type="System.Collections.Generic.IEnumerable&lt;System.Type&gt;" />
      </Parameters>
      <Docs>
        <param name="serviceInterfaceType">Dienst-Benutzeroberfläche</param>
        <param name="responseBodyTypes">Rückgabetypen für alle Methoden in der serviceInterfaceType</param>
        <summary>
            Erstellt eine IServiceRemotingResponseMessageBodySerializer für eine ServiceInterface mit DataContract-Implementierung
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>