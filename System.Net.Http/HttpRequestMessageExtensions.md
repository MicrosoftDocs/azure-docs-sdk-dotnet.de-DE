<Type Name="HttpRequestMessageExtensions" FullName="System.Net.Http.HttpRequestMessageExtensions">
  <TypeSignature Language="C#" Value="public static class HttpRequestMessageExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit HttpRequestMessageExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Net.Http.HttpRequestMessageExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module HttpRequestMessageExtensions" />
  <TypeSignature Language="F#" Value="type HttpRequestMessageExtensions = class" />
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
            Erweiterungsmethoden für <see cref="T:System.Net.Http.HttpRequestMessage" /> verschiedene Hilfsprogramme bereitstellen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateBadRequestResponse">
      <MemberSignature Language="C#" Value="public static System.Net.Http.HttpResponseMessage CreateBadRequestResponse (this System.Net.Http.HttpRequestMessage request);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.Http.HttpResponseMessage CreateBadRequestResponse(class System.Net.Http.HttpRequestMessage request) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Net.Http.HttpRequestMessageExtensions.CreateBadRequestResponse(System.Net.Http.HttpRequestMessage)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateBadRequestResponse (request As HttpRequestMessage) As HttpResponseMessage" />
      <MemberSignature Language="F#" Value="static member CreateBadRequestResponse : System.Net.Http.HttpRequestMessage -&gt; System.Net.Http.HttpResponseMessage" Usage="System.Net.Http.HttpRequestMessageExtensions.CreateBadRequestResponse request" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", Justification="Parameters are validated by Create due to how extension methods are resolved.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Net.Http.HttpResponseMessage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" RefType="this" />
      </Parameters>
      <Docs>
        <param name="request">Der aktuelle <see cref="T:System.Net.Http.HttpRequestMessage" />.</param>
        <summary>
            Erstellt ein <see cref="T:System.Net.Http.HttpResponseMessage" /> mit einem <see cref="F:System.Net.HttpStatusCode.BadRequest" /> Statuscode und den Standardwert <see cref="T:System.Web.Http.HttpError" /> als HTTP-Antworttext.
            </summary>
        <returns>Eine initialisierte <see cref="T:System.Net.Http.HttpResponseMessage" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateBadRequestResponse">
      <MemberSignature Language="C#" Value="public static System.Net.Http.HttpResponseMessage CreateBadRequestResponse (this System.Net.Http.HttpRequestMessage request, string format, params object[] args);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.Http.HttpResponseMessage CreateBadRequestResponse(class System.Net.Http.HttpRequestMessage request, string format, object[] args) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Net.Http.HttpRequestMessageExtensions.CreateBadRequestResponse(System.Net.Http.HttpRequestMessage,System.String,System.Object[])" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateBadRequestResponse (request As HttpRequestMessage, format As String, ParamArray args As Object()) As HttpResponseMessage" />
      <MemberSignature Language="F#" Value="static member CreateBadRequestResponse : System.Net.Http.HttpRequestMessage * string * obj[] -&gt; System.Net.Http.HttpResponseMessage" Usage="System.Net.Http.HttpRequestMessageExtensions.CreateBadRequestResponse (request, format, args)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", Justification="Parameters are validated by Create due to how extension methods are resolved.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Net.Http.HttpResponseMessage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" RefType="this" />
        <Parameter Name="format" Type="System.String" />
        <Parameter Name="args" Type="System.Object[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="request">Der aktuelle <see cref="T:System.Net.Http.HttpRequestMessage" />.</param>
        <param name="format">Eine kombinierte Formatzeichenfolge.</param>
        <param name="args">Ein Objektarray mit 0 (null) oder mehr zu formatierenden Objekten.</param>
        <summary>
            Erstellt ein <see cref="T:System.Net.Http.HttpResponseMessage" /> mit einer <see cref="F:System.Net.HttpStatusCode.BadRequest" /> Statuscode und einen <see cref="T:System.Web.Http.HttpError" /> mit der angegebenen Meldung als HTTP-Antworttext.
            </summary>
        <returns>Eine initialisierte <see cref="T:System.Net.Http.HttpResponseMessage" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateNotFoundResponse">
      <MemberSignature Language="C#" Value="public static System.Net.Http.HttpResponseMessage CreateNotFoundResponse (this System.Net.Http.HttpRequestMessage request);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.Http.HttpResponseMessage CreateNotFoundResponse(class System.Net.Http.HttpRequestMessage request) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Net.Http.HttpRequestMessageExtensions.CreateNotFoundResponse(System.Net.Http.HttpRequestMessage)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateNotFoundResponse (request As HttpRequestMessage) As HttpResponseMessage" />
      <MemberSignature Language="F#" Value="static member CreateNotFoundResponse : System.Net.Http.HttpRequestMessage -&gt; System.Net.Http.HttpResponseMessage" Usage="System.Net.Http.HttpRequestMessageExtensions.CreateNotFoundResponse request" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", Justification="Parameters are validated by Create due to how extension methods are resolved.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Net.Http.HttpResponseMessage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" RefType="this" />
      </Parameters>
      <Docs>
        <param name="request">Der aktuelle <see cref="T:System.Net.Http.HttpRequestMessage" />.</param>
        <summary>
            Erstellt ein <see cref="T:System.Net.Http.HttpResponseMessage" /> mit einem <see cref="F:System.Net.HttpStatusCode.NotFound" /> Statuscode und den Standardwert <see cref="T:System.Web.Http.HttpError" /> als HTTP-Antworttext.
            </summary>
        <returns>Eine initialisierte <see cref="T:System.Net.Http.HttpResponseMessage" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateNotFoundResponse">
      <MemberSignature Language="C#" Value="public static System.Net.Http.HttpResponseMessage CreateNotFoundResponse (this System.Net.Http.HttpRequestMessage request, string format, params object[] args);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.Http.HttpResponseMessage CreateNotFoundResponse(class System.Net.Http.HttpRequestMessage request, string format, object[] args) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Net.Http.HttpRequestMessageExtensions.CreateNotFoundResponse(System.Net.Http.HttpRequestMessage,System.String,System.Object[])" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateNotFoundResponse (request As HttpRequestMessage, format As String, ParamArray args As Object()) As HttpResponseMessage" />
      <MemberSignature Language="F#" Value="static member CreateNotFoundResponse : System.Net.Http.HttpRequestMessage * string * obj[] -&gt; System.Net.Http.HttpResponseMessage" Usage="System.Net.Http.HttpRequestMessageExtensions.CreateNotFoundResponse (request, format, args)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", Justification="Parameters are validated by Create due to how extension methods are resolved.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Net.Http.HttpResponseMessage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" RefType="this" />
        <Parameter Name="format" Type="System.String" />
        <Parameter Name="args" Type="System.Object[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="request">Der aktuelle <see cref="T:System.Net.Http.HttpRequestMessage" />.</param>
        <param name="format">Eine kombinierte Formatzeichenfolge.</param>
        <param name="args">Ein Objektarray mit 0 (null) oder mehr zu formatierenden Objekten.</param>
        <summary>
            Erstellt ein <see cref="T:System.Net.Http.HttpResponseMessage" /> mit einer <see cref="F:System.Net.HttpStatusCode.NotFound" /> Statuscode und einen <see cref="T:System.Web.Http.HttpError" /> mit der angegebenen Meldung als HTTP-Antworttext.
            </summary>
        <returns>Eine initialisierte <see cref="T:System.Net.Http.HttpResponseMessage" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateUnauthorizedResponse">
      <MemberSignature Language="C#" Value="public static System.Net.Http.HttpResponseMessage CreateUnauthorizedResponse (this System.Net.Http.HttpRequestMessage request);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.Http.HttpResponseMessage CreateUnauthorizedResponse(class System.Net.Http.HttpRequestMessage request) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Net.Http.HttpRequestMessageExtensions.CreateUnauthorizedResponse(System.Net.Http.HttpRequestMessage)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateUnauthorizedResponse (request As HttpRequestMessage) As HttpResponseMessage" />
      <MemberSignature Language="F#" Value="static member CreateUnauthorizedResponse : System.Net.Http.HttpRequestMessage -&gt; System.Net.Http.HttpResponseMessage" Usage="System.Net.Http.HttpRequestMessageExtensions.CreateUnauthorizedResponse request" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", Justification="Parameters are validated by Create due to how extension methods are resolved.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Net.Http.HttpResponseMessage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" RefType="this" />
      </Parameters>
      <Docs>
        <param name="request">Der aktuelle <see cref="T:System.Net.Http.HttpRequestMessage" />.</param>
        <summary>
            Erstellt ein <see cref="T:System.Net.Http.HttpResponseMessage" /> mit einem <see cref="F:System.Net.HttpStatusCode.Unauthorized" /> Statuscode und den Standardwert <see cref="T:System.Web.Http.HttpError" /> als HTTP-Antworttext.
            </summary>
        <returns>Eine initialisierte <see cref="T:System.Net.Http.HttpResponseMessage" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateUnauthorizedResponse">
      <MemberSignature Language="C#" Value="public static System.Net.Http.HttpResponseMessage CreateUnauthorizedResponse (this System.Net.Http.HttpRequestMessage request, string format, params object[] args);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.Http.HttpResponseMessage CreateUnauthorizedResponse(class System.Net.Http.HttpRequestMessage request, string format, object[] args) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Net.Http.HttpRequestMessageExtensions.CreateUnauthorizedResponse(System.Net.Http.HttpRequestMessage,System.String,System.Object[])" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateUnauthorizedResponse (request As HttpRequestMessage, format As String, ParamArray args As Object()) As HttpResponseMessage" />
      <MemberSignature Language="F#" Value="static member CreateUnauthorizedResponse : System.Net.Http.HttpRequestMessage * string * obj[] -&gt; System.Net.Http.HttpResponseMessage" Usage="System.Net.Http.HttpRequestMessageExtensions.CreateUnauthorizedResponse (request, format, args)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", Justification="Parameters are validated by Create due to how extension methods are resolved.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Net.Http.HttpResponseMessage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" RefType="this" />
        <Parameter Name="format" Type="System.String" />
        <Parameter Name="args" Type="System.Object[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="request">Der aktuelle <see cref="T:System.Net.Http.HttpRequestMessage" />.</param>
        <param name="format">Eine kombinierte Formatzeichenfolge.</param>
        <param name="args">Ein Objektarray mit 0 (null) oder mehr zu formatierenden Objekten.</param>
        <summary>
            Erstellt ein <see cref="T:System.Net.Http.HttpResponseMessage" /> mit einer <see cref="F:System.Net.HttpStatusCode.Unauthorized" /> Statuscode und einen <see cref="T:System.Web.Http.HttpError" /> mit der angegebenen Meldung als HTTP-Antworttext.
            </summary>
        <returns>Eine initialisierte <see cref="T:System.Net.Http.HttpResponseMessage" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHeaderOrDefault">
      <MemberSignature Language="C#" Value="public static string GetHeaderOrDefault (this System.Net.Http.HttpRequestMessage request, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetHeaderOrDefault(class System.Net.Http.HttpRequestMessage request, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Net.Http.HttpRequestMessageExtensions.GetHeaderOrDefault(System.Net.Http.HttpRequestMessage,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetHeaderOrDefault (request As HttpRequestMessage, name As String) As String" />
      <MemberSignature Language="F#" Value="static member GetHeaderOrDefault : System.Net.Http.HttpRequestMessage * string -&gt; string" Usage="System.Net.Http.HttpRequestMessageExtensions.GetHeaderOrDefault (request, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" RefType="this" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="request">Die Anforderung, wo der Header gesucht.</param>
        <param name="name">Der Name des Headers.</param>
        <summary>
            Ruft den ersten HTTP-Header-Wert als einen einzelnen Wert oder <c>null</c> Falls nicht vorhanden.
            </summary>
        <returns>Der erste Wert des HTTP-Header oder <c>null</c> Falls nicht vorhanden.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsIfNoneMatch">
      <MemberSignature Language="C#" Value="public static bool IsIfNoneMatch (this System.Net.Http.HttpRequestMessage request, System.Net.Http.Headers.EntityTagHeaderValue current);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool IsIfNoneMatch(class System.Net.Http.HttpRequestMessage request, class System.Net.Http.Headers.EntityTagHeaderValue current) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Net.Http.HttpRequestMessageExtensions.IsIfNoneMatch(System.Net.Http.HttpRequestMessage,System.Net.Http.Headers.EntityTagHeaderValue)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function IsIfNoneMatch (request As HttpRequestMessage, current As EntityTagHeaderValue) As Boolean" />
      <MemberSignature Language="F#" Value="static member IsIfNoneMatch : System.Net.Http.HttpRequestMessage * System.Net.Http.Headers.EntityTagHeaderValue -&gt; bool" Usage="System.Net.Http.HttpRequestMessageExtensions.IsIfNoneMatch (request, current)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" RefType="this" />
        <Parameter Name="current" Type="System.Net.Http.Headers.EntityTagHeaderValue" />
      </Parameters>
      <Docs>
        <param name="request">Die Anforderung zu entsprechen.</param>
        <param name="current">Das aktuelle Etag der Ressource. Wenn es keine aktuelle Etag ist (d. h. die Ressource ist noch nicht vorhanden) verwenden Sie <c>null</c>.</param>
        <summary>
            Überprüft, ob die Anforderung bedingte ist ein <c>If-None-Match</c> -HTTP-Headerfeld mit einem Wert, entspricht die <paramref name="current" /> Wert. Im Fall von <c>"true"</c> Dies kann verwendet werden, um anzugeben, dass eine 304 (nicht geändert) oder einen 412 (Precondition Failed) Statuscode verwendet werden soll.
            </summary>
        <returns>Gibt <c>"true"</c> sofern von der <c>If-None-Match</c> Werten übereinstimmen, die das aktuelle Etag; oder die <c>If-None-Match</c> Wert ist "*" und <paramref name="current" /> nicht null ist; andernfalls "false".</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>