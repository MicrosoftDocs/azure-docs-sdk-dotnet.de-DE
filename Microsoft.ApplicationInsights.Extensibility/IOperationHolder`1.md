<Type Name="IOperationHolder&lt;T&gt;" FullName="Microsoft.ApplicationInsights.Extensibility.IOperationHolder&lt;T&gt;">
  <TypeSignature Language="C#" Value="public interface IOperationHolder&lt;T&gt; : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IOperationHolder`1&lt;T&gt; implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ApplicationInsights.Extensibility.IOperationHolder`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IOperationHolder(Of T)&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type IOperationHolder&lt;'T&gt; = interface&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
    <AssemblyVersion>2.3.0.0</AssemblyVersion>
    <AssemblyVersion>2.5.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="T">To be added.</typeparam>
    <summary>
            Stellt die Operation-Element, das Telemetrie enthält, die auf das Ende der Anforderung nachverfolgt wird. Vorgang kann entweder WEB Edition- oder SQL-Abhängigkeiten zugeordnet werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Telemetry">
      <MemberSignature Language="C#" Value="public T Telemetry { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !T Telemetry" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.IOperationHolder`1.Telemetry" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Telemetry As T" />
      <MemberSignature Language="F#" Value="member this.Telemetry : 'T" Usage="Microsoft.ApplicationInsights.Extensibility.IOperationHolder&lt;'T&gt;.Telemetry" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Telemetrie-Element von Interesse sind, die erstellt wird, wenn der ClientExtensions StartOperation-Funktion aufgerufen wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>