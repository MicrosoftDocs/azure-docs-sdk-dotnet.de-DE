<Type Name="ExceptionHandlingRetryResult" FullName="Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult">
  <TypeSignature Language="C#" Value="public sealed class ExceptionHandlingRetryResult : Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ExceptionHandlingRetryResult extends Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ExceptionHandlingRetryResult&#xA;Inherits ExceptionHandlingResult" />
  <TypeSignature Language="F#" Value="type ExceptionHandlingRetryResult = class&#xA;    inherit ExceptionHandlingResult" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Gibt an, die Ausnahmebehandlung Ergebnis, wenn die Anforderung vom Client zum Dienst wiederholt werden kann
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExceptionHandlingRetryResult (Exception exception, bool isTransient, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, int maxRetryCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Exception exception, bool isTransient, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, int32 maxRetryCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.#ctor(System.Exception,System.Boolean,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Int32)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult : Exception * bool * Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings * int -&gt; Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" Usage="new Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult (exception, isTransient, retrySettings, maxRetryCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="exception" Type="System.Exception" />
        <Parameter Name="isTransient" Type="System.Boolean" />
        <Parameter Name="retrySettings" Type="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings" />
        <Parameter Name="maxRetryCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="exception">Die Ausnahme, die wiederholt werden muss.</param>
        <param name="isTransient">
            Gibt an, ob dies eine vorübergehende wiederholbar Ausnahme ist.
            Vorübergehende Ausnahmen, die wiederholbar sind diejenigen, in denen die Kommunikationskanals vom Client zum Dienst noch vorhanden ist.
            Nicht vorübergehende Ausnahmen, die wiederholbar sind diejenigen, in denen wir müssen den Dienstendpunkt erneut zu beheben, bevor es versucht.
            </param>
        <param name="retrySettings">Die RetrySettings, von denen das Wartezeitintervall Herstellung herausgefunden ist.</param>
        <param name="maxRetryCount">Die maximale Anzahl der Häufigkeit, mit der die Ausnahme, die durch den ExceptionId-Parameter identifizierte für wiederholt werden muss.</param>
        <summary>
            Instanziiert die ExceptionHandlingRetryResult mit den angegebenen Argumenten.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExceptionHandlingRetryResult (Exception exception, bool isTransient, TimeSpan retryDelay, int maxRetryCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Exception exception, bool isTransient, valuetype System.TimeSpan retryDelay, int32 maxRetryCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.#ctor(System.Exception,System.Boolean,System.TimeSpan,System.Int32)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult : Exception * bool * TimeSpan * int -&gt; Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" Usage="new Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult (exception, isTransient, retryDelay, maxRetryCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="exception" Type="System.Exception" />
        <Parameter Name="isTransient" Type="System.Boolean" />
        <Parameter Name="retryDelay" Type="System.TimeSpan" />
        <Parameter Name="maxRetryCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="exception">Die Ausnahme, die wiederholt werden muss.</param>
        <param name="isTransient">
            Gibt an, ob dies eine vorübergehende wiederholbar Ausnahme ist.
            Vorübergehende Ausnahmen, die wiederholbar sind diejenigen, in denen die Kommunikationskanals vom Client zum Dienst noch vorhanden ist.
            Nicht vorübergehende Ausnahmen, die wiederholbar sind diejenigen, in denen wir müssen den Dienstendpunkt erneut zu beheben, bevor es versucht.
            </param>
        <param name="retryDelay">Das Wartezeitintervall Herstellung</param>
        <param name="maxRetryCount">Die maximale Anzahl der Häufigkeit, mit der die Ausnahme, die in der Ausnahmeparameter angegebenen für wiederholt werden muss.</param>
        <summary>
            Instanziiert die ExceptionHandlingRetryResult mit den angegebenen Argumenten.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExceptionHandlingRetryResult (string exceptionId, bool isTransient, TimeSpan retryDelay, int maxRetryCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string exceptionId, bool isTransient, valuetype System.TimeSpan retryDelay, int32 maxRetryCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.#ctor(System.String,System.Boolean,System.TimeSpan,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (exceptionId As String, isTransient As Boolean, retryDelay As TimeSpan, maxRetryCount As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult : string * bool * TimeSpan * int -&gt; Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" Usage="new Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult (exceptionId, isTransient, retryDelay, maxRetryCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="exceptionId" Type="System.String" />
        <Parameter Name="isTransient" Type="System.Boolean" />
        <Parameter Name="retryDelay" Type="System.TimeSpan" />
        <Parameter Name="maxRetryCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="exceptionId">Ein Bezeichner für die Ausnahme, die wiederholt werden muss.</param>
        <param name="isTransient">
            Gibt an, ob dies eine vorübergehende wiederholbar Ausnahme ist.
            Vorübergehende Ausnahmen, die wiederholbar sind diejenigen, in denen die Kommunikationskanals vom Client zum Dienst noch vorhanden ist.
            Nicht vorübergehende Ausnahmen, die wiederholbar sind diejenigen, in denen wir müssen den Dienstendpunkt erneut zu beheben, bevor es versucht.
            </param>
        <param name="retryDelay">Das Wartezeitintervall Herstellung</param>
        <param name="maxRetryCount">Die maximale Anzahl der Häufigkeit, mit der die Ausnahme, die durch den ExceptionId-Parameter identifizierte für wiederholt werden muss.</param>
        <summary>
            Instanziiert die ExceptionHandlingRetryResult mit den angegebenen Argumenten.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExceptionId">
      <MemberSignature Language="C#" Value="public string ExceptionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ExceptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.ExceptionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExceptionId As String" />
      <MemberSignature Language="F#" Value="member this.ExceptionId : string" Usage="Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.ExceptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Eine Zeichenfolge, die eindeutig den Typ der Ausnahme.
            </summary>
        <value>
            Eindeutige Id für diese Ausnahme ausgelöst. Diese Id wird verwendet, um zu verfolgen die Anzahl der Male, die diese Ausnahme wird wiederholt
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsTransient">
      <MemberSignature Language="C#" Value="public bool IsTransient { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsTransient" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.IsTransient" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsTransient As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsTransient : bool" Usage="Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.IsTransient" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Vorübergehende Ausnahmen, die wiederholbar sind diejenigen, in denen die Kommunikationskanals vom Client zum Dienst noch vorhanden ist.
            Nicht vorübergehende Ausnahmen, die wiederholbar sind diejenigen, in denen wir müssen den Dienstendpunkt erneut zu beheben, bevor es versucht.
            </summary>
        <value>
            "true" gibt an, dass dies eine vorübergehende wiederholbar Ausnahme ist.
            False gibt an, dass dies ein nicht vorübergehender wiederholbar Ausnahme ist.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxRetryCount">
      <MemberSignature Language="C#" Value="public int MaxRetryCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxRetryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.MaxRetryCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxRetryCount As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxRetryCount : int" Usage="Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.MaxRetryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Höchstzahl der Versuche muss dieses Ausnahmetyps Netzwerkvorgängen wiederholt werden.
            Der Standardwert ist "int". "MaxValue"
            </summary>
        <value>Max-Wiederholungsanzahl</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryDelay">
      <MemberSignature Language="C#" Value="public TimeSpan RetryDelay { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan RetryDelay" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.RetryDelay" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RetryDelay As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.RetryDelay : TimeSpan" Usage="Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.RetryDelay" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Nach dieser Verzögerung soll der Vorgang wiederholt werden.
            </summary>
        <value>Die Verzögerung, die nach dem der Vorgang wiederholt werden sollte</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>