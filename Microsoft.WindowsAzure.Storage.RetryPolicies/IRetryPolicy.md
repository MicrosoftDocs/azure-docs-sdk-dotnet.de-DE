<Type Name="IRetryPolicy" FullName="Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy">
  <TypeSignature Language="C#" Value="public interface IRetryPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IRetryPolicy" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Interface IRetryPolicy" />
  <TypeSignature Language="F#" Value="type IRetryPolicy = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Stellt eine wiederholungsrichtlinie dar.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateInstance">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy CreateInstance ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy CreateInstance() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy.CreateInstance" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateInstance () As IRetryPolicy" />
      <MemberSignature Language="F#" Value="abstract member CreateInstance : unit -&gt; Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" Usage="iRetryPolicy.CreateInstance " />
      <MemberType>Method</MemberType>
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
    <Member MemberName="ShouldRetry">
      <MemberSignature Language="C#" Value="public bool ShouldRetry (int currentRetryCount, int statusCode, Exception lastException, out TimeSpan retryInterval, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool ShouldRetry(int32 currentRetryCount, int32 statusCode, class System.Exception lastException, [out] valuetype System.TimeSpan&amp; retryInterval, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy.ShouldRetry(System.Int32,System.Int32,System.Exception,System.TimeSpan@,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ShouldRetry : int * int * Exception *  * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool" Usage="iRetryPolicy.ShouldRetry (currentRetryCount, statusCode, lastException, retryInterval, operationContext)" />
      <MemberType>Method</MemberType>
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