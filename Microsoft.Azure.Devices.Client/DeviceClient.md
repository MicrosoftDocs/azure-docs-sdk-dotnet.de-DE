<Type Name="DeviceClient" FullName="Microsoft.Azure.Devices.Client.DeviceClient">
  <TypeSignature Language="C#" Value="public sealed class DeviceClient : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeviceClient extends System.Object implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Client.DeviceClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeviceClient&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type DeviceClient = class&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Enthält Methoden, die ein Gerät verwenden können, zum Senden von Nachrichten an und vom Dienst empfangen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AbandonAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AbandonAsync (Microsoft.Azure.Devices.Client.Message message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task AbandonAsync(class Microsoft.Azure.Devices.Client.Message message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.AbandonAsync(Microsoft.Azure.Devices.Client.Message)" />
      <MemberSignature Language="F#" Value="member this.AbandonAsync : Microsoft.Azure.Devices.Client.Message -&gt; System.Threading.Tasks.Task" Usage="deviceClient.AbandonAsync message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.Azure.Devices.Client.Message" />
      </Parameters>
      <Docs>
        <param name="message">To be added.</param>
        <summary>
            Setzt eine empfangene Nachricht zurück in die Warteschlange
            </summary>
        <returns>Der Sperrbezeichner für die zuvor empfangenen Nachricht</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AbandonAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AbandonAsync (string lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task AbandonAsync(string lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.AbandonAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AbandonAsync (lockToken As String) As Task" />
      <MemberSignature Language="F#" Value="member this.AbandonAsync : string -&gt; System.Threading.Tasks.Task" Usage="deviceClient.AbandonAsync lockToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="lockToken">To be added.</param>
        <summary>
            Setzt eine empfangene Nachricht zurück in die Warteschlange
            </summary>
        <returns>Der zuvor empfangenen Nachricht</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CloseAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CloseAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.CloseAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function CloseAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.CloseAsync : unit -&gt; System.Threading.Tasks.Task" Usage="deviceClient.CloseAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Schließen Sie die Instanz DeviceClient
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CompleteAsync (Microsoft.Azure.Devices.Client.Message message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CompleteAsync(class Microsoft.Azure.Devices.Client.Message message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.CompleteAsync(Microsoft.Azure.Devices.Client.Message)" />
      <MemberSignature Language="F#" Value="member this.CompleteAsync : Microsoft.Azure.Devices.Client.Message -&gt; System.Threading.Tasks.Task" Usage="deviceClient.CompleteAsync message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.Azure.Devices.Client.Message" />
      </Parameters>
      <Docs>
        <param name="message">To be added.</param>
        <summary>
            Löscht eine empfangene Nachricht aus der Gerätewarteschlange
            </summary>
        <returns>Der zuvor empfangenen Nachricht</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CompleteAsync (string lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CompleteAsync(string lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.CompleteAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CompleteAsync (lockToken As String) As Task" />
      <MemberSignature Language="F#" Value="member this.CompleteAsync : string -&gt; System.Threading.Tasks.Task" Usage="deviceClient.CompleteAsync lockToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="lockToken">To be added.</param>
        <summary>
            Löscht eine empfangene Nachricht aus der Gerätewarteschlange
            </summary>
        <returns>Der Sperrbezeichner für die zuvor empfangenen Nachricht</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Devices.Client.DeviceClient Create (string hostname, Microsoft.Azure.Devices.Client.IAuthenticationMethod authenticationMethod);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Devices.Client.DeviceClient Create(string hostname, class Microsoft.Azure.Devices.Client.IAuthenticationMethod authenticationMethod) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.Create(System.String,Microsoft.Azure.Devices.Client.IAuthenticationMethod)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (hostname As String, authenticationMethod As IAuthenticationMethod) As DeviceClient" />
      <MemberSignature Language="F#" Value="static member Create : string * Microsoft.Azure.Devices.Client.IAuthenticationMethod -&gt; Microsoft.Azure.Devices.Client.DeviceClient" Usage="Microsoft.Azure.Devices.Client.DeviceClient.Create (hostname, authenticationMethod)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Client.DeviceClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="hostname" Type="System.String" />
        <Parameter Name="authenticationMethod" Type="Microsoft.Azure.Devices.Client.IAuthenticationMethod" />
      </Parameters>
      <Docs>
        <param name="hostname">Der vollständig qualifizierte DNS-Hostname des IoT Hub</param>
        <param name="authenticationMethod">Die Authentifizierungsmethode, die verwendet wird</param>
        <summary>
            Erstellen Sie eine Amqp DeviceClient aus einzelnen Parametern
            </summary>
        <returns>DeviceClient</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Devices.Client.DeviceClient Create (string hostname, Microsoft.Azure.Devices.Client.IAuthenticationMethod authenticationMethod, Microsoft.Azure.Devices.Client.ITransportSettings[] transportSettings);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Devices.Client.DeviceClient Create(string hostname, class Microsoft.Azure.Devices.Client.IAuthenticationMethod authenticationMethod, class Microsoft.Azure.Devices.Client.ITransportSettings[] transportSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.Create(System.String,Microsoft.Azure.Devices.Client.IAuthenticationMethod,Microsoft.Azure.Devices.Client.ITransportSettings[])" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (hostname As String, authenticationMethod As IAuthenticationMethod, transportSettings As ITransportSettings()) As DeviceClient" />
      <MemberSignature Language="F#" Value="static member Create : string * Microsoft.Azure.Devices.Client.IAuthenticationMethod * Microsoft.Azure.Devices.Client.ITransportSettings[] -&gt; Microsoft.Azure.Devices.Client.DeviceClient" Usage="Microsoft.Azure.Devices.Client.DeviceClient.Create (hostname, authenticationMethod, transportSettings)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Client.DeviceClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="hostname" Type="System.String" />
        <Parameter Name="authenticationMethod" Type="Microsoft.Azure.Devices.Client.IAuthenticationMethod" />
        <Parameter Name="transportSettings" Type="Microsoft.Azure.Devices.Client.ITransportSettings[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.Runtime.InteropServices.WindowsRuntime.ReadOnlyArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="hostname">Der vollständig qualifizierte DNS-Hostname des IoT Hub</param>
        <param name="authenticationMethod">Die Authentifizierungsmethode, die verwendet wird</param>
        <param name="transportSettings">Priorisierte Liste von TransportTypes und ihre Einstellungen</param>
        <summary>
            Erstellen Sie eine DeviceClient aus einzelnen Parametern
            </summary>
        <returns>DeviceClient</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Devices.Client.DeviceClient Create (string hostname, Microsoft.Azure.Devices.Client.IAuthenticationMethod authenticationMethod, Microsoft.Azure.Devices.Client.TransportType transportType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Devices.Client.DeviceClient Create(string hostname, class Microsoft.Azure.Devices.Client.IAuthenticationMethod authenticationMethod, valuetype Microsoft.Azure.Devices.Client.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.Create(System.String,Microsoft.Azure.Devices.Client.IAuthenticationMethod,Microsoft.Azure.Devices.Client.TransportType)" />
      <MemberSignature Language="F#" Value="static member Create : string * Microsoft.Azure.Devices.Client.IAuthenticationMethod * Microsoft.Azure.Devices.Client.TransportType -&gt; Microsoft.Azure.Devices.Client.DeviceClient" Usage="Microsoft.Azure.Devices.Client.DeviceClient.Create (hostname, authenticationMethod, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Client.DeviceClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="hostname" Type="System.String" />
        <Parameter Name="authenticationMethod" Type="Microsoft.Azure.Devices.Client.IAuthenticationMethod" />
        <Parameter Name="transportType" Type="Microsoft.Azure.Devices.Client.TransportType" />
      </Parameters>
      <Docs>
        <param name="hostname">Der vollständig qualifizierte DNS-Hostname des IoT Hub</param>
        <param name="authenticationMethod">Die Authentifizierungsmethode, die verwendet wird</param>
        <param name="transportType">TransportType verwendet (Http1 oder Amqp)</param>
        <summary>
            Erstellen Sie eine DeviceClient aus einzelnen Parametern
            </summary>
        <returns>DeviceClient</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Devices.Client.DeviceClient CreateFromConnectionString (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Devices.Client.DeviceClient CreateFromConnectionString(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.CreateFromConnectionString(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String) As DeviceClient" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string -&gt; Microsoft.Azure.Devices.Client.DeviceClient" Usage="Microsoft.Azure.Devices.Client.DeviceClient.CreateFromConnectionString connectionString" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Client.DeviceClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString">Verbindungszeichenfolge für den IoT Hub (einschließlich "DeviceID")</param>
        <summary>
            Erstellen Sie eine Amqp-Transport aus der angegebenen Verbindungszeichenfolge mit DeviceClient
            </summary>
        <returns>DeviceClient</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Devices.Client.DeviceClient CreateFromConnectionString (string connectionString, Microsoft.Azure.Devices.Client.ITransportSettings[] transportSettings);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Devices.Client.DeviceClient CreateFromConnectionString(string connectionString, class Microsoft.Azure.Devices.Client.ITransportSettings[] transportSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.CreateFromConnectionString(System.String,Microsoft.Azure.Devices.Client.ITransportSettings[])" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String, transportSettings As ITransportSettings()) As DeviceClient" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string * Microsoft.Azure.Devices.Client.ITransportSettings[] -&gt; Microsoft.Azure.Devices.Client.DeviceClient" Usage="Microsoft.Azure.Devices.Client.DeviceClient.CreateFromConnectionString (connectionString, transportSettings)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Client.DeviceClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="transportSettings" Type="Microsoft.Azure.Devices.Client.ITransportSettings[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.Runtime.InteropServices.WindowsRuntime.ReadOnlyArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="connectionString">Verbindungszeichenfolge für den IoT Hub (mit "DeviceID")</param>
        <param name="transportSettings">Priorisierte Liste von Transporten und ihre Einstellungen</param>
        <summary>
            Erstellen von DeviceClient aus der angegebenen Verbindungszeichenfolge eine priorisierte Liste von Transporte verwenden
            </summary>
        <returns>DeviceClient</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Devices.Client.DeviceClient CreateFromConnectionString (string connectionString, Microsoft.Azure.Devices.Client.TransportType transportType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Devices.Client.DeviceClient CreateFromConnectionString(string connectionString, valuetype Microsoft.Azure.Devices.Client.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.CreateFromConnectionString(System.String,Microsoft.Azure.Devices.Client.TransportType)" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string * Microsoft.Azure.Devices.Client.TransportType -&gt; Microsoft.Azure.Devices.Client.DeviceClient" Usage="Microsoft.Azure.Devices.Client.DeviceClient.CreateFromConnectionString (connectionString, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Client.DeviceClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="transportType" Type="Microsoft.Azure.Devices.Client.TransportType" />
      </Parameters>
      <Docs>
        <param name="connectionString">Verbindungszeichenfolge für den IoT Hub (einschließlich "DeviceID")</param>
        <param name="transportType">Gibt an, ob Amqp oder HTTP-Transport verwendet wird</param>
        <summary>
            Erstellen von DeviceClient aus der angegebenen Verbindungszeichenfolge mithilfe der festgelegte Transporttyp (PCL) nur HTTP-Transport ist zulässig
            </summary>
        <returns>DeviceClient</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Devices.Client.DeviceClient CreateFromConnectionString (string connectionString, string deviceId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Devices.Client.DeviceClient CreateFromConnectionString(string connectionString, string deviceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.CreateFromConnectionString(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String, deviceId As String) As DeviceClient" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string * string -&gt; Microsoft.Azure.Devices.Client.DeviceClient" Usage="Microsoft.Azure.Devices.Client.DeviceClient.CreateFromConnectionString (connectionString, deviceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Client.DeviceClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="deviceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString">IoT Hub-Bereich Verbindungszeichenfolge für den IoT Hub (ohne "DeviceID")</param>
        <param name="deviceId">ID des Geräts</param>
        <summary>
            Erstellen Sie eine DeviceClient mit Amqp-Transport aus der angegebenen Verbindungszeichenfolge (WinRT) eine HTTP-Transport aus der angegebenen Verbindungszeichenfolge mit DeviceClient erstellen
            </summary>
        <returns>DeviceClient</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Devices.Client.DeviceClient CreateFromConnectionString (string connectionString, string deviceId, Microsoft.Azure.Devices.Client.ITransportSettings[] transportSettings);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Devices.Client.DeviceClient CreateFromConnectionString(string connectionString, string deviceId, class Microsoft.Azure.Devices.Client.ITransportSettings[] transportSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.CreateFromConnectionString(System.String,System.String,Microsoft.Azure.Devices.Client.ITransportSettings[])" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String, deviceId As String, transportSettings As ITransportSettings()) As DeviceClient" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string * string * Microsoft.Azure.Devices.Client.ITransportSettings[] -&gt; Microsoft.Azure.Devices.Client.DeviceClient" Usage="Microsoft.Azure.Devices.Client.DeviceClient.CreateFromConnectionString (connectionString, deviceId, transportSettings)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Client.DeviceClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="transportSettings" Type="Microsoft.Azure.Devices.Client.ITransportSettings[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.Runtime.InteropServices.WindowsRuntime.ReadOnlyArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="connectionString">Verbindungszeichenfolge für den IoT Hub (ohne "DeviceID")</param>
        <param name="deviceId">ID des Geräts</param>
        <param name="transportSettings">Priorisierte Liste von TransportTypes und ihre Einstellungen</param>
        <summary>
            Erstellen von DeviceClient aus der angegebenen Verbindungszeichenfolge, die mithilfe der priorisierten Liste von Transporten
            </summary>
        <returns>DeviceClient</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Devices.Client.DeviceClient CreateFromConnectionString (string connectionString, string deviceId, Microsoft.Azure.Devices.Client.TransportType transportType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Devices.Client.DeviceClient CreateFromConnectionString(string connectionString, string deviceId, valuetype Microsoft.Azure.Devices.Client.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.CreateFromConnectionString(System.String,System.String,Microsoft.Azure.Devices.Client.TransportType)" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string * string * Microsoft.Azure.Devices.Client.TransportType -&gt; Microsoft.Azure.Devices.Client.DeviceClient" Usage="Microsoft.Azure.Devices.Client.DeviceClient.CreateFromConnectionString (connectionString, deviceId, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Client.DeviceClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="transportType" Type="Microsoft.Azure.Devices.Client.TransportType" />
      </Parameters>
      <Docs>
        <param name="connectionString">IoT Hub-Bereich Verbindungszeichenfolge für den IoT Hub (ohne "DeviceID")</param>
        <param name="deviceId">ID des Geräts</param>
        <param name="transportType">TransportType verwendet (Http1 oder Amqp)</param>
        <summary>
            Erstellen Sie aus der angegebenen Verbindungszeichenfolge mit den angegebenen Transporttyp DeviceClient
            </summary>
        <returns>DeviceClient</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultOperationTimeoutInMilliseconds">
      <MemberSignature Language="C#" Value="public const uint DefaultOperationTimeoutInMilliseconds = 240000;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal unsigned int32 DefaultOperationTimeoutInMilliseconds = (240000)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Client.DeviceClient.DefaultOperationTimeoutInMilliseconds" />
      <MemberSignature Language="VB.NET" Value="Public Const DefaultOperationTimeoutInMilliseconds As UInteger  = 240000" />
      <MemberSignature Language="F#" Value="val mutable DefaultOperationTimeoutInMilliseconds : uint32" Usage="Microsoft.Azure.Devices.Client.DeviceClient.DefaultOperationTimeoutInMilliseconds" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.UInt32</ReturnType>
      </ReturnValue>
      <MemberValue>240000</MemberValue>
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiagnosticSamplingPercentage">
      <MemberSignature Language="C#" Value="public int DiagnosticSamplingPercentage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 DiagnosticSamplingPercentage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Client.DeviceClient.DiagnosticSamplingPercentage" />
      <MemberSignature Language="VB.NET" Value="Public Property DiagnosticSamplingPercentage As Integer" />
      <MemberSignature Language="F#" Value="member this.DiagnosticSamplingPercentage : int with get, set" Usage="Microsoft.Azure.Devices.Client.DeviceClient.DiagnosticSamplingPercentage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="deviceClient.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTwinAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt; GetTwinAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Shared.Twin&gt; GetTwinAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.GetTwinAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetTwinAsync () As Task(Of Twin)" />
      <MemberSignature Language="F#" Value="member this.GetTwinAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;" Usage="deviceClient.GetTwinAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Rufen Sie ein Gerät und-Objekt für das aktuelle Gerät.
            </summary>
        <returns>Das Ziel-Objekt für das aktuelle Gerät</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task OpenAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task OpenAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.OpenAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function OpenAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.OpenAsync : unit -&gt; System.Threading.Tasks.Task" Usage="deviceClient.OpenAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Öffnen Sie explizit die DeviceClient-Instanz.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationTimeoutInMilliseconds">
      <MemberSignature Language="C#" Value="public uint OperationTimeoutInMilliseconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int32 OperationTimeoutInMilliseconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Client.DeviceClient.OperationTimeoutInMilliseconds" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationTimeoutInMilliseconds As UInteger" />
      <MemberSignature Language="F#" Value="member this.OperationTimeoutInMilliseconds : uint32 with get, set" Usage="Microsoft.Azure.Devices.Client.DeviceClient.OperationTimeoutInMilliseconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.UInt32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Speichert das Timeout in der Wiederholungen Vorgang verwendet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProductInfo">
      <MemberSignature Language="C#" Value="public string ProductInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProductInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Client.DeviceClient.ProductInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property ProductInfo As String" />
      <MemberSignature Language="F#" Value="member this.ProductInfo : string with get, set" Usage="Microsoft.Azure.Devices.Client.DeviceClient.ProductInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Speichert benutzerdefinierte Produktinformationen, die an die Benutzer-Agent-Zeichenfolge angefügt wird, die mit IoT Hub gesendet wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Client.Message&gt; ReceiveAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Client.Message&gt; ReceiveAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.ReceiveAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync () As Task(Of Message)" />
      <MemberSignature Language="F#" Value="member this.ReceiveAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Client.Message&gt;" Usage="deviceClient.ReceiveAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Client.Message&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Eine Meldung aus der Warteschlange mit das Standardtimeout aus.
            </summary>
        <returns>Die empfangsnachricht oder Null, wenn keine Nachricht erst das Standardtimeout aufgetreten</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Client.Message&gt; ReceiveAsync (TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Client.Message&gt; ReceiveAsync(valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.ReceiveAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (timeout As TimeSpan) As Task(Of Message)" />
      <MemberSignature Language="F#" Value="member this.ReceiveAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Client.Message&gt;" Usage="deviceClient.ReceiveAsync timeout" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Client.Message&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="timeout">To be added.</param>
        <summary>
            Empfangen von Nachrichten aus der Warteschlange mit dem angegebenen timeout
            </summary>
        <returns>Die empfangsnachricht oder Null, wenn es wurde keine Nachricht, bis der angegebene Zeitraum verstrichen ist</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RejectAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RejectAsync (Microsoft.Azure.Devices.Client.Message message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RejectAsync(class Microsoft.Azure.Devices.Client.Message message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.RejectAsync(Microsoft.Azure.Devices.Client.Message)" />
      <MemberSignature Language="F#" Value="member this.RejectAsync : Microsoft.Azure.Devices.Client.Message -&gt; System.Threading.Tasks.Task" Usage="deviceClient.RejectAsync message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.Azure.Devices.Client.Message" />
      </Parameters>
      <Docs>
        <param name="message">To be added.</param>
        <summary>
            Löscht eine empfangene Nachricht aus der Warteschlange und gibt die an den Server an, dass die Nachricht nicht verarbeitet werden konnten.
            </summary>
        <returns>Der Sperrbezeichner für die zuvor empfangenen Nachricht</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RejectAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RejectAsync (string lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RejectAsync(string lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.RejectAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RejectAsync (lockToken As String) As Task" />
      <MemberSignature Language="F#" Value="member this.RejectAsync : string -&gt; System.Threading.Tasks.Task" Usage="deviceClient.RejectAsync lockToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="lockToken">To be added.</param>
        <summary>
            Löscht eine empfangene Nachricht aus der Warteschlange und gibt die an den Server an, dass die Nachricht nicht verarbeitet werden konnten.
            </summary>
        <returns>Der zuvor empfangenen Nachricht</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Devices.Client.RetryPolicyType RetryPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Devices.Client.RetryPolicyType RetryPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Client.DeviceClient.RetryPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryPolicy As RetryPolicyType" />
      <MemberSignature Language="F#" Value="member this.RetryPolicy : Microsoft.Azure.Devices.Client.RetryPolicyType with get, set" Usage="Microsoft.Azure.Devices.Client.DeviceClient.RetryPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This method has been deprecated.  Please use Microsoft.Azure.Devices.Client.SetRetryPolicy(IRetryPolicy retryPolicy) instead.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Client.RetryPolicyType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Speichert die wiederholungsstrategie, die in die Wiederholungen Vorgang verwendet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendEventAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendEventAsync (Microsoft.Azure.Devices.Client.Message message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SendEventAsync(class Microsoft.Azure.Devices.Client.Message message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.SendEventAsync(Microsoft.Azure.Devices.Client.Message)" />
      <MemberSignature Language="F#" Value="member this.SendEventAsync : Microsoft.Azure.Devices.Client.Message -&gt; System.Threading.Tasks.Task" Usage="deviceClient.SendEventAsync message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.Azure.Devices.Client.Message" />
      </Parameters>
      <Docs>
        <param name="message">To be added.</param>
        <summary>
            Wird ein Ereignis auf Gerät Hub gesendet.
            </summary>
        <returns>Die Nachricht, die das Ereignis enthält.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendEventBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendEventBatchAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Client.Message&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SendEventBatchAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Client.Message&gt; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.SendEventBatchAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Devices.Client.Message})" />
      <MemberSignature Language="VB.NET" Value="Public Function SendEventBatchAsync (messages As IEnumerable(Of Message)) As Task" />
      <MemberSignature Language="F#" Value="member this.SendEventBatchAsync : seq&lt;Microsoft.Azure.Devices.Client.Message&gt; -&gt; System.Threading.Tasks.Task" Usage="deviceClient.SendEventBatchAsync messages" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Client.Message&gt;" />
      </Parameters>
      <Docs>
        <param name="messages">To be added.</param>
        <summary>
            Sendet einen Batch von Ereignissen an Gerät-hub
            </summary>
        <returns>Die Aufgabe, die das Ereignis enthält.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetConnectionStatusChangesHandler">
      <MemberSignature Language="C#" Value="public void SetConnectionStatusChangesHandler (Microsoft.Azure.Devices.Client.ConnectionStatusChangesHandler statusChangesHandler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void SetConnectionStatusChangesHandler(class Microsoft.Azure.Devices.Client.ConnectionStatusChangesHandler statusChangesHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.SetConnectionStatusChangesHandler(Microsoft.Azure.Devices.Client.ConnectionStatusChangesHandler)" />
      <MemberSignature Language="VB.NET" Value="Public Sub SetConnectionStatusChangesHandler (statusChangesHandler As ConnectionStatusChangesHandler)" />
      <MemberSignature Language="F#" Value="member this.SetConnectionStatusChangesHandler : Microsoft.Azure.Devices.Client.ConnectionStatusChangesHandler -&gt; unit" Usage="deviceClient.SetConnectionStatusChangesHandler statusChangesHandler" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="statusChangesHandler" Type="Microsoft.Azure.Devices.Client.ConnectionStatusChangesHandler" />
      </Parameters>
      <Docs>
        <param name="statusChangesHandler">To be added.</param>
        <summary>
            Registriert einen neuen Delegaten für den Rückruf des Verbindung-Status wurde geändert. Wenn ein Delegat bereits zugeordnet ist, wird es mit dem neuen Delegaten ersetzt werden.
            <param name="statusChangesHandler">Der Name der Methode, die den Delegaten zugeordnet.</param></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetDesiredPropertyUpdateCallback">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SetDesiredPropertyUpdateCallback (Microsoft.Azure.Devices.Client.DesiredPropertyUpdateCallback callback, object userContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SetDesiredPropertyUpdateCallback(class Microsoft.Azure.Devices.Client.DesiredPropertyUpdateCallback callback, object userContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.SetDesiredPropertyUpdateCallback(Microsoft.Azure.Devices.Client.DesiredPropertyUpdateCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function SetDesiredPropertyUpdateCallback (callback As DesiredPropertyUpdateCallback, userContext As Object) As Task" />
      <MemberSignature Language="F#" Value="member this.SetDesiredPropertyUpdateCallback : Microsoft.Azure.Devices.Client.DesiredPropertyUpdateCallback * obj -&gt; System.Threading.Tasks.Task" Usage="deviceClient.SetDesiredPropertyUpdateCallback (callback, userContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Please use SetDesiredPropertyUpdateCallbackAsync.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="Microsoft.Azure.Devices.Client.DesiredPropertyUpdateCallback" />
        <Parameter Name="userContext" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback">Rückruf aufgerufen wird, nachdem die Statusupdates empfangen und angewendet wurde</param>
        <param name="userContext">Context-Objekt, das an den Rückruf übergeben werden.</param>
        <summary>
            Legen Sie einen Rückruf, der aufgerufen wird, wenn der Client ein Update Zustand (DSC oder gemeldet) vom Dienst empfängt.  Dies hat den Nebeneffekt, dass die PATCH-Thema für den Dienst abonnieren.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetDesiredPropertyUpdateCallbackAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SetDesiredPropertyUpdateCallbackAsync (Microsoft.Azure.Devices.Client.DesiredPropertyUpdateCallback callback, object userContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SetDesiredPropertyUpdateCallbackAsync(class Microsoft.Azure.Devices.Client.DesiredPropertyUpdateCallback callback, object userContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.SetDesiredPropertyUpdateCallbackAsync(Microsoft.Azure.Devices.Client.DesiredPropertyUpdateCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function SetDesiredPropertyUpdateCallbackAsync (callback As DesiredPropertyUpdateCallback, userContext As Object) As Task" />
      <MemberSignature Language="F#" Value="member this.SetDesiredPropertyUpdateCallbackAsync : Microsoft.Azure.Devices.Client.DesiredPropertyUpdateCallback * obj -&gt; System.Threading.Tasks.Task" Usage="deviceClient.SetDesiredPropertyUpdateCallbackAsync (callback, userContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="Microsoft.Azure.Devices.Client.DesiredPropertyUpdateCallback" />
        <Parameter Name="userContext" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback">Rückruf aufgerufen wird, nachdem die Statusupdates empfangen und angewendet wurde</param>
        <param name="userContext">Context-Objekt, das an den Rückruf übergeben werden.</param>
        <summary>
            Legen Sie einen Rückruf, der aufgerufen wird, wenn der Client ein Update Zustand (DSC oder gemeldet) vom Dienst empfängt.  Dies hat den Nebeneffekt, dass die PATCH-Thema für den Dienst abonnieren.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMethodDefaultHandlerAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SetMethodDefaultHandlerAsync (Microsoft.Azure.Devices.Client.MethodCallback methodHandler, object userContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SetMethodDefaultHandlerAsync(class Microsoft.Azure.Devices.Client.MethodCallback methodHandler, object userContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.SetMethodDefaultHandlerAsync(Microsoft.Azure.Devices.Client.MethodCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function SetMethodDefaultHandlerAsync (methodHandler As MethodCallback, userContext As Object) As Task" />
      <MemberSignature Language="F#" Value="member this.SetMethodDefaultHandlerAsync : Microsoft.Azure.Devices.Client.MethodCallback * obj -&gt; System.Threading.Tasks.Task" Usage="deviceClient.SetMethodDefaultHandlerAsync (methodHandler, userContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Devices.Client.DeviceClient/&lt;SetMethodDefaultHandlerAsync&gt;d__78))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="methodHandler" Type="Microsoft.Azure.Devices.Client.MethodCallback" />
        <Parameter Name="userContext" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="methodHandler">Der Delegat, der verwendet werden, wenn eine Methode vom Cloud-Dienst aufgerufen wird und kein Delegat vorhanden ist, die für dieses Methodennamens registriert sind.</param>
        <param name="userContext">Generische Parameter, durch den Clientcode interpretiert werden sollen.</param>
        <summary>
            Registriert einen neuen Delegaten, der für eine Methode aufgerufen wird, der einen Delegaten, der registriert wird, für dessen Namen aufweist. Mit dem neuen Delegaten wird ersetzt, wenn ein Delegat standardmäßig bereits registriert ist.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMethodHandler">
      <MemberSignature Language="C#" Value="public void SetMethodHandler (string methodName, Microsoft.Azure.Devices.Client.MethodCallback methodHandler, object userContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void SetMethodHandler(string methodName, class Microsoft.Azure.Devices.Client.MethodCallback methodHandler, object userContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.SetMethodHandler(System.String,Microsoft.Azure.Devices.Client.MethodCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub SetMethodHandler (methodName As String, methodHandler As MethodCallback, userContext As Object)" />
      <MemberSignature Language="F#" Value="member this.SetMethodHandler : string * Microsoft.Azure.Devices.Client.MethodCallback * obj -&gt; unit" Usage="deviceClient.SetMethodHandler (methodName, methodHandler, userContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Please use SetMethodHandlerAsync.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="methodName" Type="System.String" />
        <Parameter Name="methodHandler" Type="Microsoft.Azure.Devices.Client.MethodCallback" />
        <Parameter Name="userContext" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="methodName">To be added.</param>
        <param name="methodHandler">To be added.</param>
        <param name="userContext">To be added.</param>
        <summary>
            Registriert eine neue Delgate für die benannte Methode. Wenn ein Delegat bereits die benannte Methode zugeordnet ist, wird es mit dem neuen Delegaten ersetzt werden.
            <param name="methodName">Der Name der Methode, die den Delegaten zugeordnet. </param> <param name="methodHandler">Der Delegat, der verwendet werden, wenn eine Methode mit dem angegebenen Namen von Cloud-Dienst aufgerufen wird.</param> <param name="userContext">generischen Parameter durch den Clientcode interpretiert werden soll.</param></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMethodHandlerAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SetMethodHandlerAsync (string methodName, Microsoft.Azure.Devices.Client.MethodCallback methodHandler, object userContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SetMethodHandlerAsync(string methodName, class Microsoft.Azure.Devices.Client.MethodCallback methodHandler, object userContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.SetMethodHandlerAsync(System.String,Microsoft.Azure.Devices.Client.MethodCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function SetMethodHandlerAsync (methodName As String, methodHandler As MethodCallback, userContext As Object) As Task" />
      <MemberSignature Language="F#" Value="member this.SetMethodHandlerAsync : string * Microsoft.Azure.Devices.Client.MethodCallback * obj -&gt; System.Threading.Tasks.Task" Usage="deviceClient.SetMethodHandlerAsync (methodName, methodHandler, userContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Devices.Client.DeviceClient/&lt;SetMethodHandlerAsync&gt;d__77))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="methodName" Type="System.String" />
        <Parameter Name="methodHandler" Type="Microsoft.Azure.Devices.Client.MethodCallback" />
        <Parameter Name="userContext" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="methodName">To be added.</param>
        <param name="methodHandler">To be added.</param>
        <param name="userContext">To be added.</param>
        <summary>
            Registriert eine neue Delgate für die benannte Methode. Wenn ein Delegat bereits die benannte Methode zugeordnet ist, wird es mit dem neuen Delegaten ersetzt werden.
            <param name="methodName">Der Name der Methode, die den Delegaten zugeordnet. </param> <param name="methodHandler">Der Delegat, der verwendet werden, wenn eine Methode mit dem angegebenen Namen von Cloud-Dienst aufgerufen wird.</param> <param name="userContext">generischen Parameter durch den Clientcode interpretiert werden soll.</param></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetRetryPolicy">
      <MemberSignature Language="C#" Value="public void SetRetryPolicy (Microsoft.Azure.Devices.Client.IRetryPolicy retryPolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void SetRetryPolicy(class Microsoft.Azure.Devices.Client.IRetryPolicy retryPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.SetRetryPolicy(Microsoft.Azure.Devices.Client.IRetryPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Sub SetRetryPolicy (retryPolicy As IRetryPolicy)" />
      <MemberSignature Language="F#" Value="member this.SetRetryPolicy : Microsoft.Azure.Devices.Client.IRetryPolicy -&gt; unit" Usage="deviceClient.SetRetryPolicy retryPolicy" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="retryPolicy" Type="Microsoft.Azure.Devices.Client.IRetryPolicy" />
      </Parameters>
      <Docs>
        <param name="retryPolicy">To be added.</param>
        <summary>
            Legt die wiederholungsrichtlinie in die Wiederholungen Vorgang verwendet.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateReportedPropertiesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateReportedPropertiesAsync (Microsoft.Azure.Devices.Shared.TwinCollection reportedProperties);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpdateReportedPropertiesAsync(class Microsoft.Azure.Devices.Shared.TwinCollection reportedProperties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.UpdateReportedPropertiesAsync(Microsoft.Azure.Devices.Shared.TwinCollection)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateReportedPropertiesAsync (reportedProperties As TwinCollection) As Task" />
      <MemberSignature Language="F#" Value="member this.UpdateReportedPropertiesAsync : Microsoft.Azure.Devices.Shared.TwinCollection -&gt; System.Threading.Tasks.Task" Usage="deviceClient.UpdateReportedPropertiesAsync reportedProperties" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reportedProperties" Type="Microsoft.Azure.Devices.Shared.TwinCollection" />
      </Parameters>
      <Docs>
        <param name="reportedProperties">Gemeldeten Eigenschaften mithilfe von Push übertragen</param>
        <summary>
            Push gemeldete Eigenschaft Änderungen bis zu dem Dienst.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadToBlobAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UploadToBlobAsync (string blobName, System.IO.Stream source);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UploadToBlobAsync(string blobName, class System.IO.Stream source) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.UploadToBlobAsync(System.String,System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Function UploadToBlobAsync (blobName As String, source As Stream) As Task" />
      <MemberSignature Language="F#" Value="member this.UploadToBlobAsync : string * System.IO.Stream -&gt; System.Threading.Tasks.Task" Usage="deviceClient.UploadToBlobAsync (blobName, source)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blobName" Type="System.String" />
        <Parameter Name="source" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="blobName"></param>
        <param name="source"></param>
        <summary>
            Lädt einen Datenstrom in ein Blockblob in einem mit dem IoTHub. bei diesem Gerät verbundenen Speicherkonto hoch.
            Wenn das Blob bereits vorhanden ist, wird sie überschrieben.
            </summary>
        <returns>AsncTask</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>