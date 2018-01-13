<Type Name="FabricObjectClosedException" FullName="System.Fabric.FabricObjectClosedException">
  <TypeSignature Language="C#" Value="public class FabricObjectClosedException : System.Fabric.FabricException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit FabricObjectClosedException extends System.Fabric.FabricException" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricObjectClosedException" />
  <TypeSignature Language="VB.NET" Value="Public Class FabricObjectClosedException&#xA;Inherits FabricException" />
  <TypeSignature Language="F#" Value="type FabricObjectClosedException = class&#xA;    inherit FabricException" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.FabricException</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("StyleCop.CSharp.MaintainabilityRules", "SA1402:FileMayOnlyContainASingleClass", Justification="Exception")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para>
            Die Ausnahme, die ausgelöst wird, wenn das Service Fabric Objekt derzeit im Zustand "geschlossen" eine der folgenden Bedingungen zutrifft:
                1. Der Service Fabric-Objekt wird gelöscht.
                2. Der Service Fabric-Objekt ist nicht erreichbar, weil ein Failover.
            </para>
    </summary>
    <remarks>
      <para>Beispielsweise diese Ausnahme kann beobachtet werden, wenn ein Dienst versucht, zum Ausführen eines Vorgangs in einem Fabric-Dienst oder <see cref="T:System.Fabric.FabricReplicator" /> Objekt sich im Zustand "abgeschlossen" befindet. Ein weiteres Beispiel ist eine API aufgerufen wird, auf ein <see cref="T:System.Fabric.FabricClient" /> Objekt, wenn es sich im Zustand "abgeschlossen" befindet.</para>
      <para>
            Behandlung von <see cref="T:System.Fabric.FabricObjectClosedException" /> für <see cref="T:System.Fabric.FabricClient" /> Aufrufe: Wenn ein Aufruf FabricClient sieht <see cref="T:System.Fabric.FabricObjectClosedException" />, finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions">FabricClient Exception Handling</see> für allgemeine FabricClient Fehlerbehandlung.
                </para>
      <para>
            Behandlung von <see cref="T:System.Fabric.FabricObjectClosedException" /> für <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-reliable-collections">zuverlässige Sammlungen</see> :
                1. Wenn der Dienst erkennt <see cref="T:System.Fabric.FabricObjectClosedException" /> in <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.services.runtime.statefulservicebase.runasync?viewFallbackFrom=servicefabricsvcs#Microsoft_ServiceFabric_Services_Runtime_StatefulServiceBase_RunAsync_System_Threading_CancellationToken_">Coredispatcher</see>, sollten sie die Ausnahmen abfangen und Zurückgeben von <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.services.runtime.statefulservicebase.runasync?viewFallbackFrom=servicefabricsvcs#Microsoft_ServiceFabric_Services_Runtime_StatefulServiceBase_RunAsync_System_Threading_CancellationToken_">Coredispatcher</see>.
                    Die <see cref="T:System.Threading.CancellationToken" /> übergeben <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.services.runtime.statefulservicebase.runasync?viewFallbackFrom=servicefabricsvcs#Microsoft_ServiceFabric_Services_Runtime_StatefulServiceBase_RunAsync_System_Threading_CancellationToken_">Coredispatcher</see> signalisiert werden würde. Alle Hintergrundaufgaben sollte die Ausführung abgeschlossen, wenn dieser Abbruch signalisiert wird.
                    2. Wenn der Dienst erkennt <see cref="T:System.Fabric.FabricObjectClosedException" /> während der Verarbeitung einer Clientanforderung (z. B. über ihre Kommunikation Listener), der Dienst sollte die Ausnahme an dem Client auf dem Client sollte es den Dienst erneut aufzulösen, um das neue primäre suchen zu signalisieren.
                
            [HINWEIS] Wenn ein <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestate?view=azure-dotnet">IReliableState</see> entfernt wurde, über <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestatemanager.removeasync?view=azure-dotnet#Microsoft_ServiceFabric_Data_IReliableStateManager_RemoveAsync_Microsoft_ServiceFabric_Data_ITransaction_System_Uri_System_TimeSpan_">IReliableStateManager.RemoveAsync()</see>, alle Aufrufe, die versuchen, den Zugriff auf dieses <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestate?view=azure-dotnet">IReliableState</see> sehen <see cref="T:System.Fabric.FabricObjectClosedException" />. Diese Aufrufe mit synchronisiert werden, muss die <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestatemanager.removeasync?view=azure-dotnet#Microsoft_ServiceFabric_Data_IReliableStateManager_RemoveAsync_Microsoft_ServiceFabric_Data_ITransaction_System_Uri_System_TimeSpan_">IReliableStateManager.RemoveAsync()</see> aufrufen und sollten wissen, dass die <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestate?view=azure-dotnet">IReliableState</see> entfernt wurde.
            Die Vorgehensweisen in diesem Fall sind:
            1. Erstellen der <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestate?view=azure-dotnet">IReliableState</see> Wenn es entfernt wurde, und wiederholen Sie den Vorgang.
            2. Ignorieren der <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestate?view=azure-dotnet">IReliableState</see> und Verarbeiten von anderen <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestate?view=azure-dotnet">IReliableState</see> im Dienst.
                3. Verwenden Sie sperren, um die Racebedingung zu vermeiden. Daher innerhalb ein Remove-Aufruf der Benutzer kann beendet die Verarbeitung der <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestate?view=azure-dotnet">IReliableState</see> weiter.
                </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricObjectClosedException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricObjectClosedException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricObjectClosedException" /> Klasse mit dem Fehlercode <see cref="F:System.Fabric.FabricErrorCode.Unknown" />.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricObjectClosedException (System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricObjectClosedException.#ctor(System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricObjectClosedException : System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricObjectClosedException" Usage="new System.Fabric.FabricObjectClosedException errorCode" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="errorCode" Type="System.Fabric.FabricErrorCode" />
      </Parameters>
      <Docs>
        <param name="errorCode">
          <para>Der Fehlercode, der der Ausnahme zugeordnet wird.</para>
        </param>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricObjectClosedException" /> -Klasse mit einem angegebenen Fehlercode.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricObjectClosedException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricObjectClosedException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricObjectClosedException : string -&gt; System.Fabric.FabricObjectClosedException" Usage="new System.Fabric.FabricObjectClosedException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">
          <para>Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</para>
        </param>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricObjectClosedException" /> Klasse mit dem Fehlercode <see cref="F:System.Fabric.FabricErrorCode.Unknown" /> und einer angegebenen Fehlermeldung.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected FabricObjectClosedException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricObjectClosedException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricObjectClosedException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; System.Fabric.FabricObjectClosedException" Usage="new System.Fabric.FabricObjectClosedException (info, context)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info">
          <para>Die <see cref="T:System.Runtime.Serialization.SerializationInfo" /> -Objekt mit serialisierten Objektdaten für die ausgelöste Ausnahme.</para>
        </param>
        <param name="context">
          <para>Das <see cref="T:System.Runtime.Serialization.StreamingContext" />-Objekt, das die Kontextinformationen für die Quelle oder das Ziel enthält. Der Kontextparameter ist für die zukünftige Verwendung reserviert und kann null sein.</para>
        </param>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricObjectClosedException" /> Klasse aus einem serialisierten Objekt, mit einem angegebenen Kontext.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricObjectClosedException (string message, Exception inner);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricObjectClosedException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricObjectClosedException : string * Exception -&gt; System.Fabric.FabricObjectClosedException" Usage="new System.Fabric.FabricObjectClosedException (message, inner)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="inner" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message">
          <para>Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</para>
        </param>
        <param name="inner">
          <para>Die Ausnahme, die die Ursache der aktuellen Ausnahme oder Null ist, wenn keine innere Ausnahme angegeben wird. Die <see cref="T:System.Exception" /> Klasse erhalten Sie weitere Informationen zur inneren Ausnahme.</para>
        </param>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricObjectClosedException" /> Klasse mit einer angegebenen Fehlermeldung und einem Verweis auf die innere Ausnahme, die diese Ausnahme ausgelöst hat.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricObjectClosedException (string message, System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricObjectClosedException.#ctor(System.String,System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricObjectClosedException : string * System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricObjectClosedException" Usage="new System.Fabric.FabricObjectClosedException (message, errorCode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="errorCode" Type="System.Fabric.FabricErrorCode" />
      </Parameters>
      <Docs>
        <param name="message">
          <para>Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</para>
        </param>
        <param name="errorCode">
          <para>Der Fehlercode, der der Ausnahme zugeordnet wird.</para>
        </param>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricObjectClosedException" />-Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected FabricObjectClosedException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context, System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context, valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricObjectClosedException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext,System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext, errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricObjectClosedException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext * System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricObjectClosedException" Usage="new System.Fabric.FabricObjectClosedException (info, context, errorCode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
        <Parameter Name="errorCode" Type="System.Fabric.FabricErrorCode" />
      </Parameters>
      <Docs>
        <param name="info">
          <para>Die <see cref="T:System.Runtime.Serialization.SerializationInfo" /> -Objekt mit serialisierten Objektdaten für die ausgelöste Ausnahme.</para>
        </param>
        <param name="context">
          <para>Das <see cref="T:System.Runtime.Serialization.StreamingContext" />-Objekt, das die Kontextinformationen für die Quelle oder das Ziel enthält. Der Kontextparameter ist für die zukünftige Verwendung reserviert und kann null sein.</para>
        </param>
        <param name="errorCode">
          <para>Der Fehlercode, der der Ausnahme zugeordnet wird.</para>
        </param>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricObjectClosedException" /> -Klasse aus einem serialisierten Objektdaten mit angegebenen Kontext und Fehlercode.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricObjectClosedException (string message, Exception inner, System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner, valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricObjectClosedException.#ctor(System.String,System.Exception,System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception, errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricObjectClosedException : string * Exception * System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricObjectClosedException" Usage="new System.Fabric.FabricObjectClosedException (message, inner, errorCode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="inner" Type="System.Exception" />
        <Parameter Name="errorCode" Type="System.Fabric.FabricErrorCode" />
      </Parameters>
      <Docs>
        <param name="message">
          <para>Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</para>
        </param>
        <param name="inner">
          <para>Die Ausnahme, die die Ursache der aktuellen Ausnahme oder Null ist, wenn keine innere Ausnahme angegeben wird. Die <see cref="T:System.Exception" /> Klasse erhalten Sie weitere Informationen zur inneren Ausnahme.</para>
        </param>
        <param name="errorCode">
          <para>Der Fehlercode, der der Ausnahme zugeordnet wird.</para>
        </param>
        <summary>
          <para>
            Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricObjectClosedException" /> Nachricht Klasse mit einer angegebenen Fehlermeldung, der einen Verweis auf die innere Ausnahme, die die Ursache dieser Ausnahme und eine angegebene Fehlercode ist.
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>