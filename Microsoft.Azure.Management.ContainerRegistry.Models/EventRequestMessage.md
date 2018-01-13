<Type Name="EventRequestMessage" FullName="Microsoft.Azure.Management.ContainerRegistry.Models.EventRequestMessage">
  <TypeSignature Language="C#" Value="public class EventRequestMessage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EventRequestMessage extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerRegistry.Models.EventRequestMessage" />
  <TypeSignature Language="VB.NET" Value="Public Class EventRequestMessage" />
  <TypeSignature Language="F#" Value="type EventRequestMessage = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Die Ereignis-Anforderungsnachricht gesendet, um den Dienst-URI.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventRequestMessage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.EventRequestMessage.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der EventRequestMessage-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventRequestMessage (Microsoft.Azure.Management.ContainerRegistry.Models.EventContent content = null, System.Collections.Generic.IDictionary&lt;string,string&gt; headers = null, string method = null, string requestUri = null, string version = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.ContainerRegistry.Models.EventContent content, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; headers, string method, string requestUri, string version) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.EventRequestMessage.#ctor(Microsoft.Azure.Management.ContainerRegistry.Models.EventContent,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional content As EventContent = null, Optional headers As IDictionary(Of String, String) = null, Optional method As String = null, Optional requestUri As String = null, Optional version As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ContainerRegistry.Models.EventRequestMessage : Microsoft.Azure.Management.ContainerRegistry.Models.EventContent * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * string * string -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.EventRequestMessage" Usage="new Microsoft.Azure.Management.ContainerRegistry.Models.EventRequestMessage (content, headers, method, requestUri, version)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="content" Type="Microsoft.Azure.Management.ContainerRegistry.Models.EventContent" />
        <Parameter Name="headers" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="method" Type="System.String" />
        <Parameter Name="requestUri" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="content">Der Inhalt der Anforderungsnachricht Ereignis.</param>
        <param name="headers">Die Header der Anforderungsnachricht Ereignis.</param>
        <param name="method">Die HTTP-Methode verwendet, um die ereignismeldung für die Anforderung zu senden.</param>
        <param name="requestUri">Der URI verwendet, um die ereignismeldung für die Anforderung zu senden.</param>
        <param name="version">Die HTTP-Nachrichtenversion.</param>
        <summary>
            Initialisiert eine neue Instanz der EventRequestMessage-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Content">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ContainerRegistry.Models.EventContent Content { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ContainerRegistry.Models.EventContent Content" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.EventRequestMessage.Content" />
      <MemberSignature Language="VB.NET" Value="Public Property Content As EventContent" />
      <MemberSignature Language="F#" Value="member this.Content : Microsoft.Azure.Management.ContainerRegistry.Models.EventContent with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.EventRequestMessage.Content" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="content")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.EventContent</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Inhalt der Anforderungsnachricht Ereignis fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Headers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Headers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Headers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.EventRequestMessage.Headers" />
      <MemberSignature Language="VB.NET" Value="Public Property Headers As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Headers : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.EventRequestMessage.Headers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="headers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Header der Anforderungsnachricht Ereignis.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Method">
      <MemberSignature Language="C#" Value="public string Method { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Method" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.EventRequestMessage.Method" />
      <MemberSignature Language="VB.NET" Value="Public Property Method As String" />
      <MemberSignature Language="F#" Value="member this.Method : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.EventRequestMessage.Method" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="method")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die HTTP-Methode verwendet, um die ereignismeldung für die Anforderung zu senden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestUri">
      <MemberSignature Language="C#" Value="public string RequestUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequestUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.EventRequestMessage.RequestUri" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestUri As String" />
      <MemberSignature Language="F#" Value="member this.RequestUri : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.EventRequestMessage.RequestUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="requestUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder definiert den URI verwendet, um die ereignismeldung für die Anforderung zu senden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public string Version { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.EventRequestMessage.Version" />
      <MemberSignature Language="VB.NET" Value="Public Property Version As String" />
      <MemberSignature Language="F#" Value="member this.Version : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.EventRequestMessage.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="version")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die HTTP-Nachrichtenversion ab oder legt sie fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>