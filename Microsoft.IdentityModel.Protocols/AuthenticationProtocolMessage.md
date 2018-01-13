<Type Name="AuthenticationProtocolMessage" FullName="Microsoft.IdentityModel.Protocols.AuthenticationProtocolMessage">
  <TypeSignature Language="C#" Value="public abstract class AuthenticationProtocolMessage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit AuthenticationProtocolMessage extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Protocols.AuthenticationProtocolMessage" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class AuthenticationProtocolMessage" />
  <TypeSignature Language="F#" Value="type AuthenticationProtocolMessage = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
    <AssemblyVersion>2.1.3.0</AssemblyVersion>
    <AssemblyVersion>5.2.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            die Basisklasse für Authentifizierungsnachrichten-Protokoll.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected AuthenticationProtocolMessage ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Protocols.AuthenticationProtocolMessage.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine Standardinstanz von die <see cref="T:Microsoft.IdentityModel.Protocols.AuthenticationProtocolMessage" /> Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BuildFormPost">
      <MemberSignature Language="C#" Value="public virtual string BuildFormPost ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string BuildFormPost() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Protocols.AuthenticationProtocolMessage.BuildFormPost" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BuildFormPost () As String" />
      <MemberSignature Language="F#" Value="abstract member BuildFormPost : unit -&gt; string&#xA;override this.BuildFormPost : unit -&gt; string" Usage="authenticationProtocolMessage.BuildFormPost " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Erstellt eine Formular-Post, verwenden die aktuellen IssuerAddress und die Parameter, die festgelegt wurden.
            </summary>
        <returns>Festlegen von HTML mit Head Titel, Text, der mit einem Hiden aus mit der Aktion = IssuerAddress-Eigenschaft.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BuildRedirectUrl">
      <MemberSignature Language="C#" Value="public virtual string BuildRedirectUrl ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string BuildRedirectUrl() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Protocols.AuthenticationProtocolMessage.BuildRedirectUrl" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BuildRedirectUrl () As String" />
      <MemberSignature Language="F#" Value="abstract member BuildRedirectUrl : unit -&gt; string&#xA;override this.BuildRedirectUrl : unit -&gt; string" Usage="authenticationProtocolMessage.BuildRedirectUrl " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Erstellt eine Url, die mit der aktuellen IssuerAddress und die Parameter, die festgelegt wurden.
            </summary>
        <returns>Codierte Zeichenfolge.</returns>
        <remarks>Jeder Parameter &lt;Schlüssel, Wert&gt; wird zuerst mit umgewandelt <see cref="M:System.Uri.EscapeDataString(System.String)" />.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetParameter">
      <MemberSignature Language="C#" Value="public virtual string GetParameter (string parameter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string GetParameter(string parameter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Protocols.AuthenticationProtocolMessage.GetParameter(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetParameter (parameter As String) As String" />
      <MemberSignature Language="F#" Value="abstract member GetParameter : string -&gt; string&#xA;override this.GetParameter : string -&gt; string" Usage="authenticationProtocolMessage.GetParameter parameter" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="parameter">Der Name des Parameters.</param>
        <summary>
            Gibt einen Parameter zurück.
            </summary>
        <returns>Der Wert des Parameters oder Null, wenn der Parameter nicht vorhanden ist.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Wenn der Parameter null ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="IssuerAddress">
      <MemberSignature Language="C#" Value="public string IssuerAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IssuerAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Protocols.AuthenticationProtocolMessage.IssuerAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property IssuerAddress As String" />
      <MemberSignature Language="F#" Value="member this.IssuerAddress : string with get, set" Usage="Microsoft.IdentityModel.Protocols.AuthenticationProtocolMessage.IssuerAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Ausstelleradresse ab oder legt sie fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Wenn die "Value" null ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Parameters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Protocols.AuthenticationProtocolMessage.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Parameters As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Parameters : System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.IdentityModel.Protocols.AuthenticationProtocolMessage.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Nachrichtenparameter als ein Wörterbuch ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PostTitle">
      <MemberSignature Language="C#" Value="public string PostTitle { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PostTitle" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Protocols.AuthenticationProtocolMessage.PostTitle" />
      <MemberSignature Language="VB.NET" Value="Public Property PostTitle As String" />
      <MemberSignature Language="F#" Value="member this.PostTitle : string with get, set" Usage="Microsoft.IdentityModel.Protocols.AuthenticationProtocolMessage.PostTitle" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder definiert den Titel, der beim Erstellen der Post-Zeichenfolge verwendet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Wenn die "Value" null ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveParameter">
      <MemberSignature Language="C#" Value="public virtual void RemoveParameter (string parameter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RemoveParameter(string parameter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Protocols.AuthenticationProtocolMessage.RemoveParameter(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub RemoveParameter (parameter As String)" />
      <MemberSignature Language="F#" Value="abstract member RemoveParameter : string -&gt; unit&#xA;override this.RemoveParameter : string -&gt; unit" Usage="authenticationProtocolMessage.RemoveParameter parameter" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="parameter">Der Name des Parameters.</param>
        <summary>
            Entfernt einen Parameter an.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Wenn "Parameter" null oder leer ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="ScriptButtonText">
      <MemberSignature Language="C#" Value="public string ScriptButtonText { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ScriptButtonText" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Protocols.AuthenticationProtocolMessage.ScriptButtonText" />
      <MemberSignature Language="VB.NET" Value="Public Property ScriptButtonText As String" />
      <MemberSignature Language="F#" Value="member this.ScriptButtonText : string with get, set" Usage="Microsoft.IdentityModel.Protocols.AuthenticationProtocolMessage.ScriptButtonText" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Text der Schaltfläche Skript verwendet, wenn die Post-Zeichenfolge erstellen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Wenn die "Value" null ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="ScriptDisabledText">
      <MemberSignature Language="C#" Value="public string ScriptDisabledText { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ScriptDisabledText" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Protocols.AuthenticationProtocolMessage.ScriptDisabledText" />
      <MemberSignature Language="VB.NET" Value="Public Property ScriptDisabledText As String" />
      <MemberSignature Language="F#" Value="member this.ScriptDisabledText : string with get, set" Usage="Microsoft.IdentityModel.Protocols.AuthenticationProtocolMessage.ScriptDisabledText" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Text verwendet, wenn die Post-Zeichenfolge zu erstellen, die angezeigt wird, verwendet, wenn das Skript deaktiviert ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Wenn die "Value" null ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="SetParameter">
      <MemberSignature Language="C#" Value="public void SetParameter (string parameter, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void SetParameter(string parameter, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Protocols.AuthenticationProtocolMessage.SetParameter(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub SetParameter (parameter As String, value As String)" />
      <MemberSignature Language="F#" Value="member this.SetParameter : string * string -&gt; unit" Usage="authenticationProtocolMessage.SetParameter (parameter, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameter" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="parameter">Der Name des Parameters.</param>
        <param name="value">Der Wert, der Parameter zugewiesen werden soll.</param>
        <summary>
            Legt einen Parameter auf das Wörterbuch der Parameter.
            </summary>
        <remarks>Wenn Null als Wert übergeben wird, und der Parameter vorhanden ist, wird dieser Parameter entfernt.</remarks>
        <exception cref="T:System.ArgumentNullException">Wenn "ParameterName" null oder leer ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="SetParameters">
      <MemberSignature Language="C#" Value="public virtual void SetParameters (System.Collections.Specialized.NameValueCollection nameValueCollection);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SetParameters(class System.Collections.Specialized.NameValueCollection nameValueCollection) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Protocols.AuthenticationProtocolMessage.SetParameters(System.Collections.Specialized.NameValueCollection)" />
      <MemberSignature Language="F#" Value="abstract member SetParameters : System.Collections.Specialized.NameValueCollection -&gt; unit&#xA;override this.SetParameters : System.Collections.Specialized.NameValueCollection -&gt; unit" Usage="authenticationProtocolMessage.SetParameters nameValueCollection" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nameValueCollection" Type="System.Collections.Specialized.NameValueCollection" />
      </Parameters>
      <Docs>
        <param name="nameValueCollection"></param>
        <summary>
            Eine Auflistung festgelegt Parameter.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>