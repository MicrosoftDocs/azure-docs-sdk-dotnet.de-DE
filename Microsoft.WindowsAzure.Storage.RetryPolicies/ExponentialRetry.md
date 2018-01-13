<Type Name="ExponentialRetry" FullName="Microsoft.WindowsAzure.Storage.RetryPolicies.ExponentialRetry">
  <TypeSignature Language="C#" Value="public sealed class ExponentialRetry : Microsoft.WindowsAzure.Storage.RetryPolicies.IExtendedRetryPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ExponentialRetry extends System.Object implements class Microsoft.WindowsAzure.Storage.RetryPolicies.IExtendedRetryPolicy, class Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.RetryPolicies.ExponentialRetry" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ExponentialRetry&#xA;Implements IExtendedRetryPolicy" />
  <TypeSignature Language="F#" Value="type ExponentialRetry = class&#xA;    interface IExtendedRetryPolicy&#xA;    interface IRetryPolicy" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.WindowsAzure.Storage.RetryPolicies.IExtendedRetryPolicy</InterfaceName>
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
      <MemberSignature Language="C#" Value="public ExponentialRetry ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.RetryPolicies.ExponentialRetry.#ctor" />
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
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.ExponentialRetry" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExponentialRetry (TimeSpan deltaBackoff, int maxAttempts);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.TimeSpan deltaBackoff, int32 maxAttempts) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.RetryPolicies.ExponentialRetry.#ctor(System.TimeSpan,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (deltaBackoff As TimeSpan, maxAttempts As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.RetryPolicies.ExponentialRetry : TimeSpan * int -&gt; Microsoft.WindowsAzure.Storage.RetryPolicies.ExponentialRetry" Usage="new Microsoft.WindowsAzure.Storage.RetryPolicies.ExponentialRetry (deltaBackoff, maxAttempts)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="deltaBackoff" Type="System.TimeSpan" />
        <Parameter Name="maxAttempts" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="deltaBackoff">Ein <see cref="T:System.TimeSpan" /> das Backoff-Intervall zwischen den Wiederholungen angeben.</param>
        <param name="maxAttempts">Eine ganze Zahl, die die maximale Anzahl der Wiederholungsversuche angibt.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.ExponentialRetry" /> -Klasse mit dem angegebenen Delta und die maximale Anzahl von Wiederholungsversuchen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateInstance">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy CreateInstance ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy CreateInstance() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.RetryPolicies.ExponentialRetry.CreateInstance" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateInstance () As IRetryPolicy" />
      <MemberSignature Language="F#" Value="abstract member CreateInstance : unit -&gt; Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy&#xA;override this.CreateInstance : unit -&gt; Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" Usage="exponentialRetry.CreateInstance " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy.CreateInstance</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Generiert eine neue wiederholungsrichtlinie für den aktuellen Anforderungsversuch.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" /> Objekt, das die wiederholungsrichtlinie für den aktuellen Anforderungsversuch darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Evaluate">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo Evaluate (Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext retryContext, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo Evaluate(class Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext retryContext, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.RetryPolicies.ExponentialRetry.Evaluate(Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member Evaluate : Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo&#xA;override this.Evaluate : Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo" Usage="exponentialRetry.Evaluate (retryContext, operationContext)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.RetryPolicies.IExtendedRetryPolicy.Evaluate(Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext,Microsoft.WindowsAzure.Storage.OperationContext)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="retryContext" Type="Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="retryContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext" /> -Objekt, das die weist darauf hin wiederholt, die Ergebnisse der letzten Anforderung und, ob der nächste Versuch sollte in der primären oder sekundären Speicherort erfolgen, und gibt den Positionsmodus an.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Bestimmt, ob der Vorgang wiederholt werden sollte und das Intervall bis zur nächsten Wiederholung.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo" /> -Objekt, das den Positionsmodus gibt an, und gibt an, ob der nächste Versuch am primären oder sekundären Speicherort geschehen soll. Wenn <c>null</c>, der Vorgang wird nicht wiederholt werden.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ShouldRetry">
      <MemberSignature Language="C#" Value="public bool ShouldRetry (int currentRetryCount, int statusCode, Exception lastException, out TimeSpan retryInterval, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool ShouldRetry(int32 currentRetryCount, int32 statusCode, class System.Exception lastException, [out] valuetype System.TimeSpan&amp; retryInterval, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.RetryPolicies.ExponentialRetry.ShouldRetry(System.Int32,System.Int32,System.Exception,System.TimeSpan@,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ShouldRetry : int * int * Exception *  * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool&#xA;override this.ShouldRetry : int * int * Exception *  * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool" Usage="exponentialRetry.ShouldRetry (currentRetryCount, statusCode, lastException, retryInterval, operationContext)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy.ShouldRetry(System.Int32,System.Int32,System.Exception,System.TimeSpan@,Microsoft.WindowsAzure.Storage.OperationContext)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentRetryCount" Type="System.Int32" />
        <Parameter Name="statusCode" Type="System.Int32" />
        <Parameter Name="lastException" Type="System.Exception" />
        <Parameter Name="retryInterval" Type="System.TimeSpan&amp;" RefType="out" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="currentRetryCount">Eine ganze Zahl, die die Anzahl der Wiederholungsversuche für den angegebenen Vorgang angeben. Wert 0 (null) gibt an, dass dies der erste Fehler aufgetreten ist.</param>
        <param name="statusCode">Eine ganze Zahl, die den Statuscode für den letzten Vorgang enthält.</param>
        <param name="lastException">Ein <see cref="T:System.Exception" /> -Objekt, das die letzte ermittelte Ausnahme darstellt.</param>
        <param name="retryInterval">Ein <see cref="T:System.TimeSpan" /> , der angibt, des Wartezeitintervall bis zur nächsten Wiederholung.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Bestimmt, ob der Vorgang wiederholt werden sollte und das Intervall bis zur nächsten Wiederholung.
            </summary>
        <returns>
          <c>"true"</c> , wenn der Vorgang wiederholt; andernfalls werden soll <c>"false"</c>.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>