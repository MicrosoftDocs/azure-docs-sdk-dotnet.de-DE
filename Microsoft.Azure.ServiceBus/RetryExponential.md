<Type Name="RetryExponential" FullName="Microsoft.Azure.ServiceBus.RetryExponential">
  <TypeSignature Language="C#" Value="public sealed class RetryExponential : Microsoft.Azure.ServiceBus.RetryPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit RetryExponential extends Microsoft.Azure.ServiceBus.RetryPolicy" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.RetryExponential" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RetryExponential&#xA;Inherits RetryPolicy" />
  <TypeSignature Language="F#" Value="type RetryExponential = class&#xA;    inherit RetryPolicy" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>0.0.6.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.ServiceBus.RetryPolicy</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            RetryPolicy-Implementierung, in denen die Verzögerung zwischen den Wiederholungsversuchen exponentiellen gestaffelt anwächst.
            RetryIntervals wird mithilfe einer RetryFactor also eine Funktion der DeltaBackOff (MaximumBackoff - MinimumBackoff) berechnet werden und MaximumRetryCount
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RetryExponential (TimeSpan minimumBackoff, TimeSpan maximumBackoff, int maximumRetryCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.TimeSpan minimumBackoff, valuetype System.TimeSpan maximumBackoff, int32 maximumRetryCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.RetryExponential.#ctor(System.TimeSpan,System.TimeSpan,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (minimumBackoff As TimeSpan, maximumBackoff As TimeSpan, maximumRetryCount As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.RetryExponential : TimeSpan * TimeSpan * int -&gt; Microsoft.Azure.ServiceBus.RetryExponential" Usage="new Microsoft.Azure.ServiceBus.RetryExponential (minimumBackoff, maximumBackoff, maximumRetryCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="minimumBackoff" Type="System.TimeSpan" />
        <Parameter Name="maximumBackoff" Type="System.TimeSpan" />
        <Parameter Name="maximumRetryCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="minimumBackoff">Minimale Backoff-Intervall.</param>
        <param name="maximumBackoff">Maximale Backoff-Intervall.</param>
        <param name="maximumRetryCount">Maximale Anzahl von Wiederholungsversuchen.</param>
        <summary>
            Gibt ein neues RetryExponential wiederholen Sie den Gruppenrichtlinien-Objekt zurück.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeltaBackoff">
      <MemberSignature Language="C#" Value="public TimeSpan DeltaBackoff { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan DeltaBackoff" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.RetryExponential.DeltaBackoff" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeltaBackoff As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.DeltaBackoff : TimeSpan" Usage="Microsoft.Azure.ServiceBus.RetryExponential.DeltaBackoff" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder definiert das Backoff-Intervall, das die Wiederholung zugeordnet.
            </summary>
        <value>Das Backoff-Intervall, das die Wiederholung zugeordnet ist.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaximumBackoff">
      <MemberSignature Language="C#" Value="public TimeSpan MaximumBackoff { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan MaximumBackoff" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.RetryExponential.MaximumBackoff" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaximumBackoff As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.MaximumBackoff : TimeSpan" Usage="Microsoft.Azure.ServiceBus.RetryExponential.MaximumBackoff" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die maximale Backoff-Intervall.
            </summary>
        <value>Das maximale backoffintervall.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxRetryCount">
      <MemberSignature Language="C#" Value="public int MaxRetryCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxRetryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.RetryExponential.MaxRetryCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxRetryCount As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxRetryCount : int" Usage="Microsoft.Azure.ServiceBus.RetryExponential.MaxRetryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die maximale Anzahl von zulässigen Wiederholungen.
            </summary>
        <value>Die maximale Anzahl von zulässigen Wiederholungen.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinimalBackoff">
      <MemberSignature Language="C#" Value="public TimeSpan MinimalBackoff { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan MinimalBackoff" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.RetryExponential.MinimalBackoff" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MinimalBackoff As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.MinimalBackoff : TimeSpan" Usage="Microsoft.Azure.ServiceBus.RetryExponential.MinimalBackoff" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Minimale Backoff-Intervall.
            </summary>
        <value>Das Intervall für minimale Wartezeit.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnShouldRetry">
      <MemberSignature Language="C#" Value="protected override bool OnShouldRetry (TimeSpan remainingTime, int currentRetryCount, out TimeSpan retryInterval);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool OnShouldRetry(valuetype System.TimeSpan remainingTime, int32 currentRetryCount, [out] valuetype System.TimeSpan&amp; retryInterval) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.RetryExponential.OnShouldRetry(System.TimeSpan,System.Int32,System.TimeSpan@)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnShouldRetry (remainingTime As TimeSpan, currentRetryCount As Integer, ByRef retryInterval As TimeSpan) As Boolean" />
      <MemberSignature Language="F#" Value="override this.OnShouldRetry : TimeSpan * int *  -&gt; bool" Usage="retryExponential.OnShouldRetry (remainingTime, currentRetryCount, retryInterval)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
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
        <param name="remainingTime">Die verbleibende Zeit, bevor das Timeout abläuft.</param>
        <param name="currentRetryCount">Die Anzahl der Versuche, die verarbeitet wurden.</param>
        <param name="retryInterval">Die Zeitspanne zu verzögern, bevor Sie versuchen Sie es erneut.</param>
        <summary>
            Wird aufgerufen, um festzustellen, ob ein erneuter Versuch ausgeführt werden soll.
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>