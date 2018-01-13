<Type Name="IExtendedRetryPolicy" FullName="Microsoft.WindowsAzure.Storage.RetryPolicies.IExtendedRetryPolicy">
  <TypeSignature Language="C#" Value="public interface IExtendedRetryPolicy : Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IExtendedRetryPolicy implements class Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.RetryPolicies.IExtendedRetryPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Interface IExtendedRetryPolicy&#xA;Implements IRetryPolicy" />
  <TypeSignature Language="F#" Value="type IExtendedRetryPolicy = interface&#xA;    interface IRetryPolicy" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Stellt eine wiederholungsrichtlinie dar.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Evaluate">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo Evaluate (Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext retryContext, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo Evaluate(class Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext retryContext, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.RetryPolicies.IExtendedRetryPolicy.Evaluate(Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member Evaluate : Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo" Usage="iExtendedRetryPolicy.Evaluate (retryContext, operationContext)" />
      <MemberType>Method</MemberType>
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
  </Members>
</Type>