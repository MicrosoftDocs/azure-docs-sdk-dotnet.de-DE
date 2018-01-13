<Type Name="ServiceRemotingMessageHeaders" FullName="Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders">
  <TypeSignature Language="C#" Value="public class ServiceRemotingMessageHeaders" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServiceRemotingMessageHeaders extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceRemotingMessageHeaders" />
  <TypeSignature Language="F#" Value="type ServiceRemotingMessageHeaders = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="ServiceMessageHeaders", Namespace="urn:ServiceFabric.Communication")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Gibt die Header an, die zusammen mit einer Meldung ServiceRemoting gesendet werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceRemotingMessageHeaders ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der ServiceRemotingMessageHeaders-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddHeader">
      <MemberSignature Language="C#" Value="public void AddHeader (string headerName, byte[] headerValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void AddHeader(string headerName, unsigned int8[] headerValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders.AddHeader(System.String,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub AddHeader (headerName As String, headerValue As Byte())" />
      <MemberSignature Language="F#" Value="member this.AddHeader : string * byte[] -&gt; unit" Usage="serviceRemotingMessageHeaders.AddHeader (headerName, headerValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="headerName" Type="System.String" />
        <Parameter Name="headerValue" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="headerName">Der Name-Header.</param>
        <param name="headerValue">Der Headerwert.</param>
        <summary>
            Fügt einen neuen Header mit dem angegebenen Namen und Wert hinzu.
            Löst FabricElementAlreadyExistsException aus, wenn ein Header mit dem gleichen Namen bereits vorhanden ist.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Deserialize">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders Deserialize (System.Runtime.Serialization.DataContractSerializer serializer, byte[] buffer);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders Deserialize(class System.Runtime.Serialization.DataContractSerializer serializer, unsigned int8[] buffer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders.Deserialize(System.Runtime.Serialization.DataContractSerializer,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Deserialize (serializer As DataContractSerializer, buffer As Byte()) As ServiceRemotingMessageHeaders" />
      <MemberSignature Language="F#" Value="static member Deserialize : System.Runtime.Serialization.DataContractSerializer * byte[] -&gt; Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders" Usage="Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders.Deserialize (serializer, buffer)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serializer" Type="System.Runtime.Serialization.DataContractSerializer" />
        <Parameter Name="buffer" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="serializer">Das Deserialisierungsprogramm.</param>
        <param name="buffer">Der Puffer.</param>
        <summary>
            Deserialisierung wird das Bytearray in ein ServiceRemotingMessageHeaders-Objekt.
            </summary>
        <returns>Deserialisiert Header.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InterfaceId">
      <MemberSignature Language="C#" Value="public int InterfaceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 InterfaceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders.InterfaceId" />
      <MemberSignature Language="VB.NET" Value="Public Property InterfaceId As Integer" />
      <MemberSignature Language="F#" Value="member this.InterfaceId : int with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders.InterfaceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(IsRequired=true, Name="InterfaceId", Order=1)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Schnittstellen-Id der remote-Schnittstelle.
            </summary>
        <value>Der Schnittstellen-Id.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvocationId">
      <MemberSignature Language="C#" Value="public string InvocationId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InvocationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders.InvocationId" />
      <MemberSignature Language="VB.NET" Value="Public Property InvocationId As String" />
      <MemberSignature Language="F#" Value="member this.InvocationId : string with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders.InvocationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="InvocationId", Order=3)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Bezeichner für die remote-Methodenaufruf.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MethodId">
      <MemberSignature Language="C#" Value="public int MethodId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MethodId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders.MethodId" />
      <MemberSignature Language="VB.NET" Value="Public Property MethodId As Integer" />
      <MemberSignature Language="F#" Value="member this.MethodId : int with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders.MethodId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(IsRequired=true, Name="MethodId", Order=0)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest MethodId der remote-Methode.
            </summary>
        <value>Die Methoden-ID.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Serialize">
      <MemberSignature Language="C#" Value="public static byte[] Serialize (System.Runtime.Serialization.DataContractSerializer serializer, Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders msg);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig unsigned int8[] Serialize(class System.Runtime.Serialization.DataContractSerializer serializer, class Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders msg) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders.Serialize(System.Runtime.Serialization.DataContractSerializer,Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Serialize (serializer As DataContractSerializer, msg As ServiceRemotingMessageHeaders) As Byte()" />
      <MemberSignature Language="F#" Value="static member Serialize : System.Runtime.Serialization.DataContractSerializer * Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders -&gt; byte[]" Usage="Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders.Serialize (serializer, msg)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serializer" Type="System.Runtime.Serialization.DataContractSerializer" />
        <Parameter Name="msg" Type="Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders" />
      </Parameters>
      <Docs>
        <param name="serializer">Das Serialisierungsprogramm.</param>
        <param name="msg">Die Header.</param>
        <summary>
            Serialisiert den Header in ein Bytearray.
            </summary>
        <returns>Das serialisierte Bytearray.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGetHeaderValue">
      <MemberSignature Language="C#" Value="public bool TryGetHeaderValue (string headerName, out byte[] headerValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool TryGetHeaderValue(string headerName, [out] unsigned int8[]&amp; headerValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders.TryGetHeaderValue(System.String,System.Byte[]@)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryGetHeaderValue (headerName As String, ByRef headerValue As Byte()) As Boolean" />
      <MemberSignature Language="F#" Value="member this.TryGetHeaderValue : string *  -&gt; bool" Usage="serviceRemotingMessageHeaders.TryGetHeaderValue (headerName, headerValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="headerName" Type="System.String" />
        <Parameter Name="headerValue" Type="System.Byte[]&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="headerName">Der Name-Header.</param>
        <param name="headerValue">Der Headerwert.</param>
        <summary>
            Ruft den Header mit dem angegebenen Namen ab.
            </summary>
        <returns>"true", wenn ein Header mit diesem Namen vorhanden ist. andernfalls "false".</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>