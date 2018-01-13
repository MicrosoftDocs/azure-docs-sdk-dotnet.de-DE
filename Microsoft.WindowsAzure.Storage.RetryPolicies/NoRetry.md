<Type Name="NoRetry" FullName="Microsoft.WindowsAzure.Storage.RetryPolicies.NoRetry">
  <TypeSignature Language="C#" Value="public sealed class NoRetry : Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NoRetry extends System.Object implements class Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.RetryPolicies.NoRetry" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NoRetry&#xA;Implements IRetryPolicy" />
  <TypeSignature Language="F#" Value="type NoRetry = class&#xA;    interface IRetryPolicy" />
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
      <InterfaceName>Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Stellt eine wiederholungsrichtlinie auf, die keine Wiederholungen ausgeführt.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NoRetry ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.RetryPolicies.NoRetry.#ctor" />
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
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.NoRetry" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateInstance">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy CreateInstance ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy CreateInstance() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.RetryPolicies.NoRetry.CreateInstance" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateInstance () As IRetryPolicy" />
      <MemberSignature Language="F#" Value="abstract member CreateInstance : unit -&gt; Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy&#xA;override this.CreateInstance : unit -&gt; Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" Usage="noRetry.CreateInstance " />
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
    <Member MemberName="ShouldRetry">
      <MemberSignature Language="C#" Value="public bool ShouldRetry (int currentRetryCount, int statusCode, Exception lastException, out TimeSpan retryInterval, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool ShouldRetry(int32 currentRetryCount, int32 statusCode, class System.Exception lastException, [out] valuetype System.TimeSpan&amp; retryInterval, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.RetryPolicies.NoRetry.ShouldRetry(System.Int32,System.Int32,System.Exception,System.TimeSpan@,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ShouldRetry : int * int * Exception *  * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool&#xA;override this.ShouldRetry : int * int * Exception *  * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool" Usage="noRetry.ShouldRetry (currentRetryCount, statusCode, lastException, retryInterval, operationContext)" />
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
            Bestimmt, ob der Vorgang wiederholt werden und wie lange bis zum nächsten Versuch gewartet werden soll. 
            </summary>
        <returns>
          <c>"true"</c> , wenn der Vorgang wiederholt; andernfalls werden soll <c>"false"</c>.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>