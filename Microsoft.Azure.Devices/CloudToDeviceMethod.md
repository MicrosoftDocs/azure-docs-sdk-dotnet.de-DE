<Type Name="CloudToDeviceMethod" FullName="Microsoft.Azure.Devices.CloudToDeviceMethod">
  <TypeSignature Language="C#" Value="public class CloudToDeviceMethod" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CloudToDeviceMethod extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.CloudToDeviceMethod" />
  <TypeSignature Language="VB.NET" Value="Public Class CloudToDeviceMethod" />
  <TypeSignature Language="F#" Value="type CloudToDeviceMethod = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Parameter für eine direkte Methode auf dem Gerät ausgeführt werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudToDeviceMethod (string methodName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string methodName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.CloudToDeviceMethod.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (methodName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.CloudToDeviceMethod : string -&gt; Microsoft.Azure.Devices.CloudToDeviceMethod" Usage="new Microsoft.Azure.Devices.CloudToDeviceMethod methodName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="methodName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="methodName">Methodenname</param>
        <summary>
            Erstellt eine Instanz des Typs CloudToDeviceMethod mit 0 (null) timeout
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">Wenn <b>MethodName</b> ist Null oder leer</exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudToDeviceMethod (string methodName, TimeSpan responseTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string methodName, valuetype System.TimeSpan responseTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.CloudToDeviceMethod.#ctor(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (methodName As String, responseTimeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.CloudToDeviceMethod : string * TimeSpan -&gt; Microsoft.Azure.Devices.CloudToDeviceMethod" Usage="new Microsoft.Azure.Devices.CloudToDeviceMethod (methodName, responseTimeout)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="methodName" Type="System.String" />
        <Parameter Name="responseTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="methodName">Methodenname</param>
        <param name="responseTimeout">Timeout der Methode</param>
        <summary>
            Erstellt eine Instanz des Typs CloudToDeviceMethod mit 0 (null) timeout
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">Wenn <b>MethodName</b> ist Null oder leer</exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudToDeviceMethod (string methodName, TimeSpan responseTimeout, TimeSpan connectionTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string methodName, valuetype System.TimeSpan responseTimeout, valuetype System.TimeSpan connectionTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.CloudToDeviceMethod.#ctor(System.String,System.TimeSpan,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (methodName As String, responseTimeout As TimeSpan, connectionTimeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.CloudToDeviceMethod : string * TimeSpan * TimeSpan -&gt; Microsoft.Azure.Devices.CloudToDeviceMethod" Usage="new Microsoft.Azure.Devices.CloudToDeviceMethod (methodName, responseTimeout, connectionTimeout)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="methodName" Type="System.String" />
        <Parameter Name="responseTimeout" Type="System.TimeSpan" />
        <Parameter Name="connectionTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="methodName">Methodenname</param>
        <param name="responseTimeout">Timeout der Methode</param>
        <param name="connectionTimeout">Verbindungstimeout Gerät</param>
        <summary>
            Erstellt eine Instanz des Typs CloudToDeviceMethod
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">Wenn <b>MethodName</b> ist Null oder leer</exception>
      </Docs>
    </Member>
    <Member MemberName="ConnectionTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan ConnectionTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan ConnectionTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.CloudToDeviceMethod.ConnectionTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.ConnectionTimeout : TimeSpan with get, set" Usage="Microsoft.Azure.Devices.CloudToDeviceMethod.ConnectionTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonIgnore</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Timeout für das Gerät online geschaltet werden kann
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPayloadAsJson">
      <MemberSignature Language="C#" Value="public string GetPayloadAsJson ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetPayloadAsJson() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.CloudToDeviceMethod.GetPayloadAsJson" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPayloadAsJson () As String" />
      <MemberSignature Language="F#" Value="member this.GetPayloadAsJson : unit -&gt; string" Usage="cloudToDeviceMethod.GetPayloadAsJson " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Laden Sie die Nutzlast als json
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MethodName">
      <MemberSignature Language="C#" Value="public string MethodName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MethodName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.CloudToDeviceMethod.MethodName" />
      <MemberSignature Language="VB.NET" Value="Public Property MethodName As String" />
      <MemberSignature Language="F#" Value="member this.MethodName : string with get, set" Usage="Microsoft.Azure.Devices.CloudToDeviceMethod.MethodName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty("methodName", Required=Newtonsoft.Json.Required.Always)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die auszuführende Methode
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResponseTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan ResponseTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan ResponseTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.CloudToDeviceMethod.ResponseTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property ResponseTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.ResponseTimeout : TimeSpan with get, set" Usage="Microsoft.Azure.Devices.CloudToDeviceMethod.ResponseTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonIgnore</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Timeout der Methode
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPayloadJson">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Devices.CloudToDeviceMethod SetPayloadJson (string json);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Devices.CloudToDeviceMethod SetPayloadJson(string json) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.CloudToDeviceMethod.SetPayloadJson(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SetPayloadJson (json As String) As CloudToDeviceMethod" />
      <MemberSignature Language="F#" Value="member this.SetPayloadJson : string -&gt; Microsoft.Azure.Devices.CloudToDeviceMethod" Usage="cloudToDeviceMethod.SetPayloadJson json" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.CloudToDeviceMethod</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="json" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="json">To be added.</param>
        <summary>
            Set-Nutzlast als json
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>