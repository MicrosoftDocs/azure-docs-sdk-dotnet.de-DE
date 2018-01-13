<Type Name="RetryExponential" FullName="Microsoft.Azure.NotificationHubs.RetryExponential">
  <TypeSignature Language="C#" Value="public sealed class RetryExponential : Microsoft.Azure.NotificationHubs.RetryPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit RetryExponential extends Microsoft.Azure.NotificationHubs.RetryPolicy" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.RetryExponential" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RetryExponential&#xA;Inherits RetryPolicy" />
  <TypeSignature Language="F#" Value="type RetryExponential = class&#xA;    inherit RetryPolicy" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.NotificationHubs.RetryPolicy</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Stellt eine wiederholungsrichtlinie auf, die eine angegebene Anzahl an Wiederholungen unter Verwendung einer zufälligen exponentiellen Backoff-Schema bestimmt das Intervall zwischen Wiederholungsversuchen ausführt.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RetryExponential (TimeSpan minBackoff, TimeSpan maxBackoff, TimeSpan deltaBackoff, TimeSpan terminationTimeBuffer, int maxRetryCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.TimeSpan minBackoff, valuetype System.TimeSpan maxBackoff, valuetype System.TimeSpan deltaBackoff, valuetype System.TimeSpan terminationTimeBuffer, int32 maxRetryCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.RetryExponential.#ctor(System.TimeSpan,System.TimeSpan,System.TimeSpan,System.TimeSpan,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (minBackoff As TimeSpan, maxBackoff As TimeSpan, deltaBackoff As TimeSpan, terminationTimeBuffer As TimeSpan, maxRetryCount As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.RetryExponential : TimeSpan * TimeSpan * TimeSpan * TimeSpan * int -&gt; Microsoft.Azure.NotificationHubs.RetryExponential" Usage="new Microsoft.Azure.NotificationHubs.RetryExponential (minBackoff, maxBackoff, deltaBackoff, terminationTimeBuffer, maxRetryCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="minBackoff" Type="System.TimeSpan" />
        <Parameter Name="maxBackoff" Type="System.TimeSpan" />
        <Parameter Name="deltaBackoff" Type="System.TimeSpan" />
        <Parameter Name="terminationTimeBuffer" Type="System.TimeSpan" />
        <Parameter Name="maxRetryCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="minBackoff">Das Intervall für minimale Wartezeit.</param>
        <param name="maxBackoff">Das maximale backoffintervall.</param>
        <param name="deltaBackoff">Das Backoff-Intervall, das die Wiederholung zugeordnet ist.</param>
        <param name="terminationTimeBuffer">Der Beendigungszeitpuffer für die Wiederholung.</param>
        <param name="maxRetryCount">Die maximale Anzahl von zulässigen versuchen Sie es erneut.</param>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.RetryExponential" />-Klasse.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public override Microsoft.Azure.NotificationHubs.RetryPolicy Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.Azure.NotificationHubs.RetryPolicy Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.RetryExponential.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Clone () As RetryPolicy" />
      <MemberSignature Language="F#" Value="override this.Clone : unit -&gt; Microsoft.Azure.NotificationHubs.RetryPolicy" Usage="retryExponential.Clone " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.RetryPolicy</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Erstellt eine neue Kopie dieser Instanz.</summary>
        <returns>Die erstellte neue Kopie dieser Instanz.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeltaBackoff">
      <MemberSignature Language="C#" Value="public TimeSpan DeltaBackoff { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan DeltaBackoff" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.RetryExponential.DeltaBackoff" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeltaBackoff As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.DeltaBackoff : TimeSpan" Usage="Microsoft.Azure.NotificationHubs.RetryExponential.DeltaBackoff" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ermittelt oder definiert das Backoff-Intervall, das die Wiederholung zugeordnet.</summary>
        <value>Das Backoff-Intervall, das die Wiederholung zugeordnet ist.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsRetryableException">
      <MemberSignature Language="C#" Value="protected override bool IsRetryableException (Exception lastException);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool IsRetryableException(class System.Exception lastException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.RetryExponential.IsRetryableException(System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function IsRetryableException (lastException As Exception) As Boolean" />
      <MemberSignature Language="F#" Value="override this.IsRetryableException : Exception -&gt; bool" Usage="retryExponential.IsRetryableException lastException" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lastException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="lastException"></param>
        <summary>
            Bestimmen Sie, ob die Ausnahme ist in Ordnung, um einen Wiederholungsversuch
            </summary>
        <returns>
            Wenn dies auf "false" zurückgeben, wird keine Wiederholung stattfinden.
            Andernfalls verwenden wir die OnShouldRetry() zum Ermitteln, wann zu wiederholen.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaximumBackoff">
      <MemberSignature Language="C#" Value="public TimeSpan MaximumBackoff { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan MaximumBackoff" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.RetryExponential.MaximumBackoff" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaximumBackoff As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.MaximumBackoff : TimeSpan" Usage="Microsoft.Azure.NotificationHubs.RetryExponential.MaximumBackoff" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die maximale Backoff-Intervall.</summary>
        <value>Das maximale backoffintervall.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxRetryCount">
      <MemberSignature Language="C#" Value="public int MaxRetryCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxRetryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.RetryExponential.MaxRetryCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxRetryCount As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxRetryCount : int" Usage="Microsoft.Azure.NotificationHubs.RetryExponential.MaxRetryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die maximale Anzahl von zulässigen versuchen Sie es erneut.</summary>
        <value>Die maximale Anzahl von zulässigen versuchen Sie es erneut.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinimalBackoff">
      <MemberSignature Language="C#" Value="public TimeSpan MinimalBackoff { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan MinimalBackoff" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.RetryExponential.MinimalBackoff" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MinimalBackoff As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.MinimalBackoff : TimeSpan" Usage="Microsoft.Azure.NotificationHubs.RetryExponential.MinimalBackoff" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt das Intervall für minimale Wartezeit fest.</summary>
        <value>Das Intervall für minimale Wartezeit.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnShouldRetry">
      <MemberSignature Language="C#" Value="protected override bool OnShouldRetry (TimeSpan remainingTime, int currentRetryCount, out TimeSpan retryInterval);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool OnShouldRetry(valuetype System.TimeSpan remainingTime, int32 currentRetryCount, [out] valuetype System.TimeSpan&amp; retryInterval) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.RetryExponential.OnShouldRetry(System.TimeSpan,System.Int32,System.TimeSpan@)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnShouldRetry (remainingTime As TimeSpan, currentRetryCount As Integer, ByRef retryInterval As TimeSpan) As Boolean" />
      <MemberSignature Language="F#" Value="override this.OnShouldRetry : TimeSpan * int *  -&gt; bool" Usage="retryExponential.OnShouldRetry (remainingTime, currentRetryCount, retryInterval)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="remainingTime" Type="System.TimeSpan" />
        <Parameter Name="currentRetryCount" Type="System.Int32" />
        <Parameter Name="retryInterval" Type="System.TimeSpan&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="remainingTime"></param>
        <param name="currentRetryCount"></param>
        <param name="retryInterval"></param>
        <summary>
            Berechnen Sie das Wiederholungsintervall für die wiederholungsrichtlinie.
            </summary>
        <returns>
            Wenn diese Methode "true" zurückgeben, erfolgt wiederholen Sie den Vorgang nach Thread RetryInteval Zeitraum im Leerlauf.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TerminationTimeBuffer">
      <MemberSignature Language="C#" Value="public TimeSpan TerminationTimeBuffer { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan TerminationTimeBuffer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.RetryExponential.TerminationTimeBuffer" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TerminationTimeBuffer As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.TerminationTimeBuffer : TimeSpan" Usage="Microsoft.Azure.NotificationHubs.RetryExponential.TerminationTimeBuffer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Abrufen oder festlegen den Beendigung Zeitpuffer, die die Wiederholung zugeordnet.</summary>
        <value>Der Beendigungszeitpuffer für die Wiederholung.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>