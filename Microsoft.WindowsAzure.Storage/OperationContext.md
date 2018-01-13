<Type Name="OperationContext" FullName="Microsoft.WindowsAzure.Storage.OperationContext">
  <TypeSignature Language="C#" Value="public sealed class OperationContext" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed OperationContext extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.OperationContext" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class OperationContext" />
  <TypeSignature Language="F#" Value="type OperationContext = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt den Kontext für einen Anforderungsvorgang für den Speicherdienst dar und bietet zusätzliche Laufzeitinformationen zu dessen Ausführung.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationContext ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.OperationContext.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientRequestID">
      <MemberSignature Language="C#" Value="public string ClientRequestID { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClientRequestID" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.OperationContext.ClientRequestID" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientRequestID As String" />
      <MemberSignature Language="F#" Value="member this.ClientRequestID : string with get, set" Usage="Microsoft.WindowsAzure.Storage.OperationContext.ClientRequestID" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Client-Anforderungs-ID
            </summary>
        <value>Eine Zeichenfolge, enthält die Clientanforderungs-ID auf.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomUserAgent">
      <MemberSignature Language="C#" Value="public string CustomUserAgent { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CustomUserAgent" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.OperationContext.CustomUserAgent" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomUserAgent As String" />
      <MemberSignature Language="F#" Value="member this.CustomUserAgent : string with get, set" Usage="Microsoft.WindowsAzure.Storage.OperationContext.CustomUserAgent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>Dieser Wert wird überschrieben werden, wenn die UserAgent Wert über SendingRequestEvent (pro Instanz oder globale) geändert wird.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultLogLevel">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.LogLevel DefaultLogLevel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property valuetype Microsoft.WindowsAzure.Storage.LogLevel DefaultLogLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.OperationContext.DefaultLogLevel" />
      <MemberSignature Language="VB.NET" Value="Public Shared Property DefaultLogLevel As LogLevel" />
      <MemberSignature Language="F#" Value="member this.DefaultLogLevel : Microsoft.WindowsAzure.Storage.LogLevel with get, set" Usage="Microsoft.WindowsAzure.Storage.OperationContext.DefaultLogLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.LogLevel</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Standardprotokolliergrad für nachfolgend erstellte Instanzen der zu verwendende der <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> Klasse.
            </summary>
        <value>Ein Wert vom Typ <see cref="P:Microsoft.WindowsAzure.Storage.OperationContext.LogLevel" /> , die angibt, welche Ereignisse standardmäßig von Instanzen der protokolliert werden die <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public DateTime EndTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.OperationContext.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public Property EndTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.EndTime : DateTime with get, set" Usage="Microsoft.WindowsAzure.Storage.OperationContext.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Endzeit des Vorgangs.
            </summary>
        <value>Ein <see cref="T:System.DateTime" /> Wert, der angibt, der Endzeit des Vorgangs.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GlobalRequestCompleted">
      <MemberSignature Language="C#" Value="public static event EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; GlobalRequestCompleted;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; GlobalRequestCompleted" />
      <MemberSignature Language="DocId" Value="E:Microsoft.WindowsAzure.Storage.OperationContext.GlobalRequestCompleted" />
      <MemberSignature Language="VB.NET" Value="Public Shared Custom Event GlobalRequestCompleted As EventHandler(Of RequestEventArgs) " />
      <MemberSignature Language="F#" Value="member this.GlobalRequestCompleted : EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; " Usage="member this.GlobalRequestCompleted : System.EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Tritt auf, nachdem eine Antwort vollständig empfangen und verarbeitet wurden.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GlobalResponseReceived">
      <MemberSignature Language="C#" Value="public static event EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; GlobalResponseReceived;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; GlobalResponseReceived" />
      <MemberSignature Language="DocId" Value="E:Microsoft.WindowsAzure.Storage.OperationContext.GlobalResponseReceived" />
      <MemberSignature Language="VB.NET" Value="Public Shared Custom Event GlobalResponseReceived As EventHandler(Of RequestEventArgs) " />
      <MemberSignature Language="F#" Value="member this.GlobalResponseReceived : EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; " Usage="member this.GlobalResponseReceived : System.EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Tritt auf, wenn eine Antwort, von dem Server, bevor das Verarbeiten empfangen wird oder herunterladen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GlobalRetrying">
      <MemberSignature Language="C#" Value="public static event EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; GlobalRetrying;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; GlobalRetrying" />
      <MemberSignature Language="DocId" Value="E:Microsoft.WindowsAzure.Storage.OperationContext.GlobalRetrying" />
      <MemberSignature Language="VB.NET" Value="Public Shared Custom Event GlobalRetrying As EventHandler(Of RequestEventArgs) " />
      <MemberSignature Language="F#" Value="member this.GlobalRetrying : EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; " Usage="member this.GlobalRetrying : System.EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Tritt ein, bevor eine Anforderung wiederholt wird.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GlobalSendingRequest">
      <MemberSignature Language="C#" Value="public static event EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; GlobalSendingRequest;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; GlobalSendingRequest" />
      <MemberSignature Language="DocId" Value="E:Microsoft.WindowsAzure.Storage.OperationContext.GlobalSendingRequest" />
      <MemberSignature Language="VB.NET" Value="Public Shared Custom Event GlobalSendingRequest As EventHandler(Of RequestEventArgs) " />
      <MemberSignature Language="F#" Value="member this.GlobalSendingRequest : EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; " Usage="member this.GlobalSendingRequest : System.EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Tritt unmittelbar vor der Signierung einer Anforderung.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastResult">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.RequestResult LastResult { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.RequestResult LastResult" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.OperationContext.LastResult" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastResult As RequestResult" />
      <MemberSignature Language="F#" Value="member this.LastResult : Microsoft.WindowsAzure.Storage.RequestResult" Usage="Microsoft.WindowsAzure.Storage.OperationContext.LastResult" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.RequestResult</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das letzte Anforderungsergebnis gefunden für den Vorgang ab.
            </summary>
        <value>Ein <see cref="T:Microsoft.WindowsAzure.Storage.RequestResult" /> -Objekt, das letzte Anforderungsergebnis darstellt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LogLevel">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.LogLevel LogLevel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.LogLevel LogLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.OperationContext.LogLevel" />
      <MemberSignature Language="VB.NET" Value="Public Property LogLevel As LogLevel" />
      <MemberSignature Language="F#" Value="member this.LogLevel : Microsoft.WindowsAzure.Storage.LogLevel with get, set" Usage="Microsoft.WindowsAzure.Storage.OperationContext.LogLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.LogLevel</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Protokolliergrad für eine Instanz von verwendet werden soll die <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> Klasse.
            </summary>
        <value>Ein Wert vom Typ <see cref="P:Microsoft.WindowsAzure.Storage.OperationContext.LogLevel" /> , die angibt, welche Ereignisse protokolliert werden, indem Sie die <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestCompleted">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; RequestCompleted;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; RequestCompleted" />
      <MemberSignature Language="DocId" Value="E:Microsoft.WindowsAzure.Storage.OperationContext.RequestCompleted" />
      <MemberSignature Language="VB.NET" Value="Public Custom Event RequestCompleted As EventHandler(Of RequestEventArgs) " />
      <MemberSignature Language="F#" Value="member this.RequestCompleted : EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; " Usage="member this.RequestCompleted : System.EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Tritt auf, nachdem eine Antwort vollständig empfangen und verarbeitet wurden.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestResults">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Storage.RequestResult&gt; RequestResults { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.WindowsAzure.Storage.RequestResult&gt; RequestResults" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.OperationContext.RequestResults" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestResults As IList(Of RequestResult)" />
      <MemberSignature Language="F#" Value="member this.RequestResults : System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Storage.RequestResult&gt;" Usage="Microsoft.WindowsAzure.Storage.OperationContext.RequestResults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Storage.RequestResult&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Satz von anforderungsergebnissen, die den aktuellen Vorgang erstellt wurde.
            </summary>
        <value>Ein <see cref="T:System.Collections.IList" /> Objekt, das enthält <see cref="T:Microsoft.WindowsAzure.Storage.RequestResult" /> Objekte, die die vom aktuellen Vorgang erstellten Anforderungsergebnisse darstellen.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResponseReceived">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; ResponseReceived;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; ResponseReceived" />
      <MemberSignature Language="DocId" Value="E:Microsoft.WindowsAzure.Storage.OperationContext.ResponseReceived" />
      <MemberSignature Language="VB.NET" Value="Public Custom Event ResponseReceived As EventHandler(Of RequestEventArgs) " />
      <MemberSignature Language="F#" Value="member this.ResponseReceived : EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; " Usage="member this.ResponseReceived : System.EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Tritt auf, wenn eine Antwort, aus dem Dienst, bevor das Verarbeiten empfangen wird oder herunterladen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Retrying">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; Retrying;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; Retrying" />
      <MemberSignature Language="DocId" Value="E:Microsoft.WindowsAzure.Storage.OperationContext.Retrying" />
      <MemberSignature Language="VB.NET" Value="Public Custom Event Retrying As EventHandler(Of RequestEventArgs) " />
      <MemberSignature Language="F#" Value="member this.Retrying : EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; " Usage="member this.Retrying : System.EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Tritt ein, bevor eine Anforderung wiederholt wird.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendingRequest">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; SendingRequest;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; SendingRequest" />
      <MemberSignature Language="DocId" Value="E:Microsoft.WindowsAzure.Storage.OperationContext.SendingRequest" />
      <MemberSignature Language="VB.NET" Value="Public Custom Event SendingRequest As EventHandler(Of RequestEventArgs) " />
      <MemberSignature Language="F#" Value="member this.SendingRequest : EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; " Usage="member this.SendingRequest : System.EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Tritt unmittelbar vor der Signierung einer Anforderung.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTime StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.OperationContext.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTime with get, set" Usage="Microsoft.WindowsAzure.Storage.OperationContext.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Startzeit des Vorgangs fest.
            </summary>
        <value>Ein <see cref="T:System.DateTime" /> Wert, der angibt, der Startzeit des Vorgangs.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserHeaders">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; UserHeaders { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; UserHeaders" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.OperationContext.UserHeaders" />
      <MemberSignature Language="VB.NET" Value="Public Property UserHeaders As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.UserHeaders : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.OperationContext.UserHeaders" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest zusätzliche Header für die Anforderung beispielsweise für Proxy- oder Protokollierungsinformation.
            </summary>
        <value>Ein <see cref="T:System.Collections.Generic.IDictionary`2" /> Objekt, das zusätzliche Headerinformationen enthält.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>