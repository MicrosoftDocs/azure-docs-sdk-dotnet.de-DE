<Type Name="OperationRetryControl" FullName="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl">
  <TypeSignature Language="C#" Value="public class OperationRetryControl" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OperationRetryControl extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl" />
  <TypeSignature Language="VB.NET" Value="Public Class OperationRetryControl" />
  <TypeSignature Language="F#" Value="type OperationRetryControl = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Gibt an, dass die wiederholungsrichtlinie für die Ausnahmen bei der Kommunikation vom Client zum Dienst erhalten.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationRetryControl ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Exception">
      <MemberSignature Language="C#" Value="public Exception Exception { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Exception Exception" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.Exception" />
      <MemberSignature Language="VB.NET" Value="Public Property Exception As Exception" />
      <MemberSignature Language="F#" Value="member this.Exception : Exception with get, set" Usage="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.Exception" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Exception</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Diese Ausnahme Bericht für den Vorgang, wenn ShouldRetry auf "false" festgelegt ist. Standardmäßig ist dies die gleiche Ausnahme wie die gemeldeten Ausnahme jedoch in einigen Fällen die Factory Trasform gemeldete Ausnahme in eine aussagekräftigere Ausnahme nach Wunsch kann.
            </summary>
        <value>Ausnahme</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExceptionId">
      <MemberSignature Language="C#" Value="public string ExceptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ExceptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.ExceptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property ExceptionId As String" />
      <MemberSignature Language="F#" Value="member this.ExceptionId : string with get, set" Usage="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.ExceptionId" />
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
        <value>Eindeutige Id für diese Ausnahme ausgelöst. Diese Id wird verwendet, um zu verfolgen die Anzahl der Male, die diese Ausnahme wird wiederholt</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsTransient">
      <MemberSignature Language="C#" Value="public bool IsTransient { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsTransient" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.IsTransient" />
      <MemberSignature Language="VB.NET" Value="Public Property IsTransient As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsTransient : bool with get, set" Usage="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.IsTransient" />
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
            Wenn die ShouldRetry-Eigenschaft auf "true" festgelegt ist, gibt diese Eigenschaft an, ob es sich bei der Kommunikationskanal zwischen dem Client und Dienst noch gültig ist.
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
      <MemberSignature Language="C#" Value="public int MaxRetryCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxRetryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.MaxRetryCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxRetryCount As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxRetryCount : int with get, set" Usage="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.MaxRetryCount" />
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
            Maximale Anzahl der Häufigkeit, mit die diesem Vorgang wiederholt werden sollte, wenn die ShouldRetry auf "true" festgelegt ist
            </summary>
        <value>Max-Wiederholungsanzahl</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryDelay">
      <MemberSignature Language="C#" Value="public TimeSpan RetryDelay { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan RetryDelay" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.RetryDelay" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryDelay As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.RetryDelay : TimeSpan with get, set" Usage="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.RetryDelay" />
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
            Der Vorgang sollte nach dieser Verzögerung erneut versucht werden, wenn die ShouldRetry auf "true" festgelegt ist.
            </summary>
        <value>Die Verzögerung, die nach dem der Vorgang wiederholt werden sollte</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ShouldRetry">
      <MemberSignature Language="C#" Value="public bool ShouldRetry { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ShouldRetry" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.ShouldRetry" />
      <MemberSignature Language="VB.NET" Value="Public Property ShouldRetry As Boolean" />
      <MemberSignature Language="F#" Value="member this.ShouldRetry : bool with get, set" Usage="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.ShouldRetry" />
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
            Gibt an, ob der Vorgang wiederholt werden soll.
            </summary>
        <value>"true", wenn der Vorgang muss wiederholt werden – "false", wenn die Ausnahme an den Benutzer ausgelöst werden soll</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>