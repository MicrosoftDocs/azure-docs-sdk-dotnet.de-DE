<Type Name="TraceWriterExtensions" FullName="System.Web.Http.TraceWriterExtensions">
  <TypeSignature Language="C#" Value="public static class TraceWriterExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit TraceWriterExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Web.Http.TraceWriterExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module TraceWriterExtensions" />
  <TypeSignature Language="F#" Value="type TraceWriterExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.ComponentModel.EditorBrowsable(System.ComponentModel.EditorBrowsableState.Never)</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Erweiterungsmethoden für <see cref="T:System.Web.Http.Tracing.ITraceWriter" /> leicht verwendbare Methoden für die Anmeldung bereitgestellt.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Debug">
      <MemberSignature Language="C#" Value="public static void Debug (this System.Web.Http.Tracing.ITraceWriter traceWriter, string message, System.Net.Http.HttpRequestMessage request = null, string category = &quot;&quot;);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Debug(class System.Web.Http.Tracing.ITraceWriter traceWriter, string message, class System.Net.Http.HttpRequestMessage request, string category) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Web.Http.TraceWriterExtensions.Debug(System.Web.Http.Tracing.ITraceWriter,System.String,System.Net.Http.HttpRequestMessage,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Debug (traceWriter As ITraceWriter, message As String, Optional request As HttpRequestMessage = null, Optional category As String = &quot;&quot;)" />
      <MemberSignature Language="F#" Value="static member Debug : System.Web.Http.Tracing.ITraceWriter * string * System.Net.Http.HttpRequestMessage * string -&gt; unit" Usage="System.Web.Http.TraceWriterExtensions.Debug (traceWriter, message, request, category)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1026:DefaultParametersShouldNotBeUsed", Justification="Default parameters are in order for log messages.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="traceWriter" Type="System.Web.Http.Tracing.ITraceWriter" RefType="this" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" />
        <Parameter Name="category" Type="System.String">
          <Attributes>
            <Attribute>
              <AttributeName>System.Runtime.CompilerServices.CallerMemberName</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="traceWriter">Der <see cref="T:System.Web.Http.Tracing.ITraceWriter" /></param>
        <param name="message">Die zu protokollierende Meldung.</param>
        <param name="request">Anforderung für die Nachrichtenkorrelation verwendet. Der Standardwert ist null.</param>
        <param name="category">Die Kategorie für die Ablaufverfolgung. Der Standardwert ist die Methode oder Eigenschaft den Namen des Aufrufers.</param>
        <summary>
            Schreibt eine <see cref="T:System.Web.Http.Tracing.TraceRecord" /> am <see cref="F:System.Web.Http.Tracing.TraceLevel.Debug" /> mit der angegebenen Meldung.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Error">
      <MemberSignature Language="C#" Value="public static void Error (this System.Web.Http.Tracing.ITraceWriter traceWriter, Exception exception, System.Net.Http.HttpRequestMessage request = null, string category = &quot;&quot;);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Error(class System.Web.Http.Tracing.ITraceWriter traceWriter, class System.Exception exception, class System.Net.Http.HttpRequestMessage request, string category) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Web.Http.TraceWriterExtensions.Error(System.Web.Http.Tracing.ITraceWriter,System.Exception,System.Net.Http.HttpRequestMessage,System.String)" />
      <MemberSignature Language="F#" Value="static member Error : System.Web.Http.Tracing.ITraceWriter * Exception * System.Net.Http.HttpRequestMessage * string -&gt; unit" Usage="System.Web.Http.TraceWriterExtensions.Error (traceWriter, exception, request, category)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1026:DefaultParametersShouldNotBeUsed", Justification="Default parameters are in order for log messages.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="traceWriter" Type="System.Web.Http.Tracing.ITraceWriter" RefType="this" />
        <Parameter Name="exception" Type="System.Exception" />
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" />
        <Parameter Name="category" Type="System.String">
          <Attributes>
            <Attribute>
              <AttributeName>System.Runtime.CompilerServices.CallerMemberName</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="traceWriter">Der <see cref="T:System.Web.Http.Tracing.ITraceWriter" /></param>
        <param name="exception">Die zu protokollierende Ausnahme.</param>
        <param name="request">Anforderung für die Nachrichtenkorrelation verwendet. Der Standardwert ist null.</param>
        <param name="category">Die Kategorie für die Ablaufverfolgung. Der Standardwert ist die Methode oder Eigenschaft den Namen des Aufrufers.</param>
        <summary>
            Schreibt eine <see cref="T:System.Web.Http.Tracing.TraceRecord" /> am <see cref="F:System.Web.Http.Tracing.TraceLevel.Error" /> mit der angegebenen <paramref name="exception" />.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Error">
      <MemberSignature Language="C#" Value="public static void Error (this System.Web.Http.Tracing.ITraceWriter traceWriter, string message, System.Net.Http.HttpRequestMessage request = null, string category = &quot;&quot;);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Error(class System.Web.Http.Tracing.ITraceWriter traceWriter, string message, class System.Net.Http.HttpRequestMessage request, string category) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Web.Http.TraceWriterExtensions.Error(System.Web.Http.Tracing.ITraceWriter,System.String,System.Net.Http.HttpRequestMessage,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Error (traceWriter As ITraceWriter, message As String, Optional request As HttpRequestMessage = null, Optional category As String = &quot;&quot;)" />
      <MemberSignature Language="F#" Value="static member Error : System.Web.Http.Tracing.ITraceWriter * string * System.Net.Http.HttpRequestMessage * string -&gt; unit" Usage="System.Web.Http.TraceWriterExtensions.Error (traceWriter, message, request, category)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1026:DefaultParametersShouldNotBeUsed", Justification="Default parameters are in order for log messages.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="traceWriter" Type="System.Web.Http.Tracing.ITraceWriter" RefType="this" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" />
        <Parameter Name="category" Type="System.String">
          <Attributes>
            <Attribute>
              <AttributeName>System.Runtime.CompilerServices.CallerMemberName</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="traceWriter">Der <see cref="T:System.Web.Http.Tracing.ITraceWriter" /></param>
        <param name="message">Die zu protokollierende Meldung.</param>
        <param name="request">Anforderung für die Nachrichtenkorrelation verwendet. Der Standardwert ist null.</param>
        <param name="category">Die Kategorie für die Ablaufverfolgung. Der Standardwert ist die Methode oder Eigenschaft den Namen des Aufrufers.</param>
        <summary>
            Schreibt eine <see cref="T:System.Web.Http.Tracing.TraceRecord" /> am <see cref="F:System.Web.Http.Tracing.TraceLevel.Error" /> mit der angegebenen Meldung.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Error">
      <MemberSignature Language="C#" Value="public static void Error (this System.Web.Http.Tracing.ITraceWriter traceWriter, string message, Exception exception, System.Net.Http.HttpRequestMessage request = null, string category = &quot;&quot;);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Error(class System.Web.Http.Tracing.ITraceWriter traceWriter, string message, class System.Exception exception, class System.Net.Http.HttpRequestMessage request, string category) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Web.Http.TraceWriterExtensions.Error(System.Web.Http.Tracing.ITraceWriter,System.String,System.Exception,System.Net.Http.HttpRequestMessage,System.String)" />
      <MemberSignature Language="F#" Value="static member Error : System.Web.Http.Tracing.ITraceWriter * string * Exception * System.Net.Http.HttpRequestMessage * string -&gt; unit" Usage="System.Web.Http.TraceWriterExtensions.Error (traceWriter, message, exception, request, category)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1026:DefaultParametersShouldNotBeUsed", Justification="Default parameters are in order for log messages.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="traceWriter" Type="System.Web.Http.Tracing.ITraceWriter" RefType="this" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="exception" Type="System.Exception" />
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" />
        <Parameter Name="category" Type="System.String">
          <Attributes>
            <Attribute>
              <AttributeName>System.Runtime.CompilerServices.CallerMemberName</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="traceWriter">Der <see cref="T:System.Web.Http.Tracing.ITraceWriter" /></param>
        <param name="message">Die zu protokollierende Meldung.</param>
        <param name="exception">Die zu protokollierende Ausnahme.</param>
        <param name="request">Anforderung für die Nachrichtenkorrelation verwendet. Der Standardwert ist null.</param>
        <param name="category">Die Kategorie für die Ablaufverfolgung. Der Standardwert ist die Methode oder Eigenschaft den Namen des Aufrufers.</param>
        <summary>
            Schreibt eine <see cref="T:System.Web.Http.Tracing.TraceRecord" /> am <see cref="F:System.Web.Http.Tracing.TraceLevel.Error" /> mit der angegebenen Meldung und Ausnahme.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Info">
      <MemberSignature Language="C#" Value="public static void Info (this System.Web.Http.Tracing.ITraceWriter traceWriter, string message, System.Net.Http.HttpRequestMessage request = null, string category = &quot;&quot;);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Info(class System.Web.Http.Tracing.ITraceWriter traceWriter, string message, class System.Net.Http.HttpRequestMessage request, string category) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Web.Http.TraceWriterExtensions.Info(System.Web.Http.Tracing.ITraceWriter,System.String,System.Net.Http.HttpRequestMessage,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Info (traceWriter As ITraceWriter, message As String, Optional request As HttpRequestMessage = null, Optional category As String = &quot;&quot;)" />
      <MemberSignature Language="F#" Value="static member Info : System.Web.Http.Tracing.ITraceWriter * string * System.Net.Http.HttpRequestMessage * string -&gt; unit" Usage="System.Web.Http.TraceWriterExtensions.Info (traceWriter, message, request, category)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1026:DefaultParametersShouldNotBeUsed", Justification="Default parameters are in order for log messages.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="traceWriter" Type="System.Web.Http.Tracing.ITraceWriter" RefType="this" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" />
        <Parameter Name="category" Type="System.String">
          <Attributes>
            <Attribute>
              <AttributeName>System.Runtime.CompilerServices.CallerMemberName</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="traceWriter">Der <see cref="T:System.Web.Http.Tracing.ITraceWriter" /></param>
        <param name="message">Die zu protokollierende Meldung.</param>
        <param name="request">Anforderung für die Nachrichtenkorrelation verwendet. Der Standardwert ist null.</param>
        <param name="category">Die Kategorie für die Ablaufverfolgung. Der Standardwert ist die Methode oder Eigenschaft den Namen des Aufrufers.</param>
        <summary>
            Schreibt eine <see cref="T:System.Web.Http.Tracing.TraceRecord" /> am <see cref="F:System.Web.Http.Tracing.TraceLevel.Info" /> mit der angegebenen Meldung.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Trace">
      <MemberSignature Language="C#" Value="public static void Trace (this System.Web.Http.Tracing.ITraceWriter traceWriter, System.Web.Http.Tracing.TraceLevel level, string message, Exception exception, System.Net.Http.HttpRequestMessage request = null, string category = &quot;&quot;);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Trace(class System.Web.Http.Tracing.ITraceWriter traceWriter, valuetype System.Web.Http.Tracing.TraceLevel level, string message, class System.Exception exception, class System.Net.Http.HttpRequestMessage request, string category) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Web.Http.TraceWriterExtensions.Trace(System.Web.Http.Tracing.ITraceWriter,System.Web.Http.Tracing.TraceLevel,System.String,System.Exception,System.Net.Http.HttpRequestMessage,System.String)" />
      <MemberSignature Language="F#" Value="static member Trace : System.Web.Http.Tracing.ITraceWriter * System.Web.Http.Tracing.TraceLevel * string * Exception * System.Net.Http.HttpRequestMessage * string -&gt; unit" Usage="System.Web.Http.TraceWriterExtensions.Trace (traceWriter, level, message, exception, request, category)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="traceWriter" Type="System.Web.Http.Tracing.ITraceWriter" RefType="this" />
        <Parameter Name="level" Type="System.Web.Http.Tracing.TraceLevel" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="exception" Type="System.Exception" />
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" />
        <Parameter Name="category" Type="System.String">
          <Attributes>
            <Attribute>
              <AttributeName>System.Runtime.CompilerServices.CallerMemberName</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="traceWriter">Der <see cref="T:System.Web.Http.Tracing.ITraceWriter" /></param>
        <param name="level">Die <see cref="T:System.Web.Http.Tracing.TraceLevel" /> für die Ablaufverfolgung.</param>
        <param name="message">Die Meldung, die Protokolldateien (oder Null).</param>
        <param name="exception">Die Ausnahme, die Protokolldateien (oder Null).</param>
        <param name="request">Anforderung für die Nachrichtenkorrelation verwendet. Der Standardwert ist null.</param>
        <param name="category">Die Kategorie für die Ablaufverfolgung. Der Standardwert ist die Methode oder Eigenschaft den Namen des Aufrufers.</param>
        <summary>
            Schreibt einen einzelnen <see cref="T:System.Web.Http.Tracing.TraceRecord" /> auf den angegebenen <see cref="T:System.Web.Http.Tracing.ITraceWriter" /> der ablaufverfolgungswriter für aktiviert ist die angegebene <paramref name="category" /> und <paramref name="level" />.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Warn">
      <MemberSignature Language="C#" Value="public static void Warn (this System.Web.Http.Tracing.ITraceWriter traceWriter, string message, System.Net.Http.HttpRequestMessage request = null, string category = &quot;&quot;);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Warn(class System.Web.Http.Tracing.ITraceWriter traceWriter, string message, class System.Net.Http.HttpRequestMessage request, string category) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Web.Http.TraceWriterExtensions.Warn(System.Web.Http.Tracing.ITraceWriter,System.String,System.Net.Http.HttpRequestMessage,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Warn (traceWriter As ITraceWriter, message As String, Optional request As HttpRequestMessage = null, Optional category As String = &quot;&quot;)" />
      <MemberSignature Language="F#" Value="static member Warn : System.Web.Http.Tracing.ITraceWriter * string * System.Net.Http.HttpRequestMessage * string -&gt; unit" Usage="System.Web.Http.TraceWriterExtensions.Warn (traceWriter, message, request, category)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1026:DefaultParametersShouldNotBeUsed", Justification="Default parameters are in order for log messages.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="traceWriter" Type="System.Web.Http.Tracing.ITraceWriter" RefType="this" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" />
        <Parameter Name="category" Type="System.String">
          <Attributes>
            <Attribute>
              <AttributeName>System.Runtime.CompilerServices.CallerMemberName</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="traceWriter">Der <see cref="T:System.Web.Http.Tracing.ITraceWriter" /></param>
        <param name="message">Die zu protokollierende Meldung.</param>
        <param name="request">Anforderung für die Nachrichtenkorrelation verwendet. Der Standardwert ist null.</param>
        <param name="category">Die Kategorie für die Ablaufverfolgung. Der Standardwert ist die Methode oder Eigenschaft den Namen des Aufrufers.</param>
        <summary>
            Schreibt eine <see cref="T:System.Web.Http.Tracing.TraceRecord" /> am <see cref="F:System.Web.Http.Tracing.TraceLevel.Warn" /> mit der angegebenen Meldung.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>