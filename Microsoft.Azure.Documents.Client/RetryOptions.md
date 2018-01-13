<Type Name="RetryOptions" FullName="Microsoft.Azure.Documents.Client.RetryOptions">
  <TypeSignature Language="C#" Value="public class RetryOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RetryOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Client.RetryOptions" />
  <TypeSignature Language="VB.NET" Value="Public Class RetryOptions" />
  <TypeSignature Language="F#" Value="type RetryOptions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            RetryOptions-Klasse definiert die Parameter, die eine Anwendung zum Anpassen der integrierten wiederholungsrichtlinien im Azure-Cosmos-DB-Dienst festlegen kann.
            </summary>
    <remarks>
            Die <see cref="T:Microsoft.Azure.Documents.Client.DocumentClient" /> Klasse unterstützt die Wiederholung auf bestimmte Arten von Ausnahmen. Diese Klasse stellt Optionen für Anwendungen zum Steuern des Verhaltens versuchen Sie es erneut.
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RetryOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.RetryOptions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Erstellt eine neue Instanz der Klasse RetryOptions und initialisieren Sie alle Eigenschaften mit Standardwerten für den Azure-Cosmos-DB-Dienst.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxRetryAttemptsOnThrottledRequests">
      <MemberSignature Language="C#" Value="public int MaxRetryAttemptsOnThrottledRequests { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxRetryAttemptsOnThrottledRequests" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.RetryOptions.MaxRetryAttemptsOnThrottledRequests" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxRetryAttemptsOnThrottledRequests As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxRetryAttemptsOnThrottledRequests : int with get, set" Usage="Microsoft.Azure.Documents.Client.RetryOptions.MaxRetryAttemptsOnThrottledRequests" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die maximale Anzahl der Wiederholungsversuche im Fall, in dem die Anforderung schlägt fehl, da der Dienst Azure-Cosmos-DB Begrenzung von aufrufraten, auf dem Client angewendet wurde.
            </summary>
        <value>
            Der Standardwert ist 9. Dies bedeutet, dass im Fall, in dem die Anforderung Rate begrenzt wird, ist, die gleiche Anforderung ausgegeben für maximal 10 Mal an den Server vor dem Fehler an die Anwendung zurückgegeben wird. Wenn der Wert dieser Eigenschaft auf 0 festgelegt ist, keine automatische Wiederholung auf Begrenzung von aufrufraten, die Clientanforderungen werden, und die Ausnahme muss auf Anwendungsebene behandelt. Ein Beispiel zum Festlegen dieses Werts finden Sie in <see cref="P:Microsoft.Azure.Documents.Client.ConnectionPolicy.RetryOptions" />.
            </value>
        <remarks>
          <para>
            Wenn ein Client fordert schneller als die zulässige Rate sendet, wird vom Dienst HttpStatusCode 429 (zu viele Anforderung) auf den Grenzwert für den Client zurückgegeben. Die aktuelle Implementierung im SDK wartet dann für den Zeitraum, den der Dienst weist warten, und wiederholen Sie dann die Zeit verstrichen ist.  
            </para>
          <para>
            Weitere Informationen finden Sie unter <see href="https://docs.microsoft.com/en-us/azure/documentdb/documentdb-performance-tips#429">Handle Rate beschränken/Anforderungsrate groß</see>.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxRetryWaitTimeInSeconds">
      <MemberSignature Language="C#" Value="public int MaxRetryWaitTimeInSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxRetryWaitTimeInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.RetryOptions.MaxRetryWaitTimeInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxRetryWaitTimeInSeconds As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxRetryWaitTimeInSeconds : int with get, set" Usage="Microsoft.Azure.Documents.Client.RetryOptions.MaxRetryWaitTimeInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die maximale Wiederholungszeit in Sekunden für den Azure-Cosmos-DB-Dienst.
            </summary>
        <value>
            Der Standardwert ist 30 Sekunden. Ein Beispiel zum Festlegen dieses Werts finden Sie in <see cref="P:Microsoft.Azure.Documents.Client.ConnectionPolicy.RetryOptions" />.
            </value>
        <remarks>
          <para>
            Bei einem aufgrund einer Begrenzung von aufrufraten, Fehler Anforderungsfehler, der Dienst sendet eine Antwort zurück, die enthält einen Wert, der angibt, der Client sollte nicht vor dem wiederholen, der <see cref="P:Microsoft.Azure.Documents.DocumentClientException.RetryAfter" /> Zeitraum verstrichen ist. Diese Eigenschaft kann die Anwendung auf eine maximalen Wartezeit festgelegt, für alle Wiederholungsversuchen.
            Wenn die kumulierte Wartezeit diesen überschreitet Wert, der Client beendet, und wiederholen Sie dann und der Fehler an die Anwendung zurückgegeben.
            </para>
          <para>
            Weitere Informationen finden Sie unter <see href="https://docs.microsoft.com/en-us/azure/documentdb/documentdb-performance-tips#429">Handle Rate beschränken/Anforderungsrate groß</see>.
            </para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>