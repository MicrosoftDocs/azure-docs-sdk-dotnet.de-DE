<Type Name="ExponentialBackoff" FullName="Microsoft.Azure.Devices.Client.ExponentialBackoff">
  <TypeSignature Language="C#" Value="public class ExponentialBackoff : Microsoft.Azure.Devices.Client.IRetryPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExponentialBackoff extends System.Object implements class Microsoft.Azure.Devices.Client.IRetryPolicy" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Client.ExponentialBackoff" />
  <TypeSignature Language="VB.NET" Value="Public Class ExponentialBackoff&#xA;Implements IRetryPolicy" />
  <TypeSignature Language="F#" Value="type ExponentialBackoff = class&#xA;    interface IRetryPolicy" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Devices.Client.IRetryPolicy</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Stellt eine wiederholungsrichtlinie auf, die eine angegebene Anzahl an Wiederholungen unter Verwendung ein zufälligen Exponentielles Backoff-Schema bestimmt das Intervall zwischen Wiederholungsversuchen ausführt.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExponentialBackoff (int retryCount, TimeSpan minBackoff, TimeSpan maxBackoff, TimeSpan deltaBackoff);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 retryCount, valuetype System.TimeSpan minBackoff, valuetype System.TimeSpan maxBackoff, valuetype System.TimeSpan deltaBackoff) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.ExponentialBackoff.#ctor(System.Int32,System.TimeSpan,System.TimeSpan,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (retryCount As Integer, minBackoff As TimeSpan, maxBackoff As TimeSpan, deltaBackoff As TimeSpan)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Client.ExponentialBackoff : int * TimeSpan * TimeSpan * TimeSpan -&gt; Microsoft.Azure.Devices.Client.ExponentialBackoff" Usage="new Microsoft.Azure.Devices.Client.ExponentialBackoff (retryCount, minBackoff, maxBackoff, deltaBackoff)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="retryCount" Type="System.Int32" />
        <Parameter Name="minBackoff" Type="System.TimeSpan" />
        <Parameter Name="maxBackoff" Type="System.TimeSpan" />
        <Parameter Name="deltaBackoff" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="retryCount">Die maximale Anzahl von Wiederholungsversuchen.</param>
        <param name="minBackoff">Die minimale Backoff-Zeit</param>
        <param name="maxBackoff">Die maximale Backoff-Zeit.</param>
        <param name="deltaBackoff">Der Wert, der verwendet wird, um einen zufälligen Delta der exponentiellen Verzögerung zwischen Wiederholungsversuchen zu berechnen.</param>
        <summary>
            Erstellt eine Instanz des ExponentialBackoff.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ShouldRetry">
      <MemberSignature Language="C#" Value="public bool ShouldRetry (int currentRetryCount, Exception lastException, out TimeSpan retryInterval);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool ShouldRetry(int32 currentRetryCount, class System.Exception lastException, [out] valuetype System.TimeSpan&amp; retryInterval) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.ExponentialBackoff.ShouldRetry(System.Int32,System.Exception,System.TimeSpan@)" />
      <MemberSignature Language="VB.NET" Value="Public Function ShouldRetry (currentRetryCount As Integer, lastException As Exception, ByRef retryInterval As TimeSpan) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member ShouldRetry : int * Exception *  -&gt; bool&#xA;override this.ShouldRetry : int * Exception *  -&gt; bool" Usage="exponentialBackoff.ShouldRetry (currentRetryCount, lastException, retryInterval)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Devices.Client.IRetryPolicy.ShouldRetry(System.Int32,System.Exception,System.TimeSpan@)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentRetryCount" Type="System.Int32" />
        <Parameter Name="lastException" Type="System.Exception" />
        <Parameter Name="retryInterval" Type="System.TimeSpan&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="currentRetryCount">Wie oft der Vorgang wiederholt wurde.</param>
        <param name="lastException">Operation-Ausnahme.</param>
        <param name="retryInterval">Nach Ablauf dieser Zeitspanne muss nächsten Wiederholung ausgeführt werden.</param>
        <summary>
            Gibt "true" zurück, wenn basieren auf den Parametern, die der Vorgang wiederholt werden sollte.
            </summary>
        <returns>"True", wenn der Vorgang wiederholt "false", andernfalls werden sollen.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>