<Type Name="SqlFilter" FullName="Microsoft.Azure.ServiceBus.SqlFilter">
  <TypeSignature Language="C#" Value="public class SqlFilter : Microsoft.Azure.ServiceBus.Filter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SqlFilter extends Microsoft.Azure.ServiceBus.Filter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.SqlFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class SqlFilter&#xA;Inherits Filter" />
  <TypeSignature Language="F#" Value="type SqlFilter = class&#xA;    inherit Filter" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.ServiceBus.Filter</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt einen Filter, der eine Komposition eines Ausdrucks ist und eine Aktion, die in der Pub/Sub-Pipeline ausgeführt wird.
            </summary>
    <remarks>
            Ein <see cref="T:Microsoft.Azure.ServiceBus.SqlFilter" /> enthält einen SQL-ähnlichen Bedingungsausdruck, der im Broker für die benutzerdefinierten Eigenschaften, die eingehenden Nachrichtenstroms und Systemeigenschaften ausgewertet wird. Alle Systemeigenschaften (alle Eigenschaften explizit aufgeführt sind auf die <see cref="T:Microsoft.Azure.ServiceBus.Message" /> Klasse) vorangestellt werden muss <code>sys.</code> im Bedingungsausdruck. Die SQL-Teilmenge implementiert Testen auf Vorhandensein von Eigenschaften (vorhanden), die Überprüfung auf Null-Werte (IS NULL), Logisches NOT/AND/OR Operatoren (relational), numerische arithmetische und einfachen Text Mustervergleich mit LIKE.
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SqlFilter (string sqlExpression);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string sqlExpression) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SqlFilter.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (sqlExpression As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.SqlFilter : string -&gt; Microsoft.Azure.ServiceBus.SqlFilter" Usage="new Microsoft.Azure.ServiceBus.SqlFilter sqlExpression" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sqlExpression" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sqlExpression">To be added.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.ServiceBus.SqlFilter" /> -Klasse unter Verwendung des angegebenen SQL-Ausdrucks.
            </summary>
        <remarks>Maximal zulässige Länge von Sql-Ausdruck ist 1024 Zeichen.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; Parameters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SqlFilter.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Parameters As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.Parameters : System.Collections.Generic.IDictionary&lt;string, obj&gt;" Usage="Microsoft.Azure.ServiceBus.SqlFilter.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Legt den Wert eines Filterausdrucks.
            </summary>
        <value>Der Wert eines Filterausdrucks.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SqlExpression">
      <MemberSignature Language="C#" Value="public string SqlExpression { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SqlExpression" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SqlFilter.SqlExpression" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SqlExpression As String" />
      <MemberSignature Language="F#" Value="member this.SqlExpression : string" Usage="Microsoft.Azure.ServiceBus.SqlFilter.SqlExpression" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den SQL-Ausdruck ab.
            </summary>
        <value>Der SQL-Ausdruck.</value>
        <remarks>Maximal zulässige Länge von Sql-Ausdruck ist 1024 Zeichen.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SqlFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="sqlFilter.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Gibt eine Zeichenfolgendarstellung <see cref="T:Microsoft.Azure.ServiceBus.SqlFilter" />.
            </summary>
        <returns>Eine Zeichenfolgendarstellung von <see cref="T:Microsoft.Azure.ServiceBus.SqlFilter" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>