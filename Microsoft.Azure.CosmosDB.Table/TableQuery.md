<Type Name="TableQuery" FullName="Microsoft.Azure.CosmosDB.Table.TableQuery">
  <TypeSignature Language="C#" Value="public class TableQuery" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TableQuery extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />
  <TypeSignature Language="VB.NET" Value="Public Class TableQuery" />
  <TypeSignature Language="F#" Value="type TableQuery = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
    <AssemblyVersion>0.9.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt eine Abfrage für eine angegebene Tabelle dar.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableQuery ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableQuery.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Stellt eine Abfrage für eine angegebene Tabelle dar.
            </summary>
        <remarks>Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> Instanz aggregiert die Abfrageparameter zu verwenden, wenn die Abfrage ausgeführt wird. Eines der <c>ExecuteQuery</c> oder <c>ExecuteQuerySegmented</c> Methoden der <see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTableClient" /> aufgerufen werden, um die Abfrage auszuführen. Die Parameter sind codiert und an den Server übergeben werden, wenn das Table-Abfrage ausgeführt wird.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CombineFilters">
      <MemberSignature Language="C#" Value="public static string CombineFilters (string filterA, string operatorString, string filterB);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string CombineFilters(string filterA, string operatorString, string filterB) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableQuery.CombineFilters(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CombineFilters (filterA As String, operatorString As String, filterB As String) As String" />
      <MemberSignature Language="F#" Value="static member CombineFilters : string * string * string -&gt; string" Usage="Microsoft.Azure.CosmosDB.Table.TableQuery.CombineFilters (filterA, operatorString, filterB)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filterA" Type="System.String" />
        <Parameter Name="operatorString" Type="System.String" />
        <Parameter Name="filterB" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="filterA">Eine Zeichenfolge, die die erste formatierte filterbedingung enthält.</param>
        <param name="operatorString">Eine Zeichenfolge mit dem Operator (AND, OR) zu verwenden.</param>
        <param name="filterB">Eine Zeichenfolge, die zweite formatierte filterbedingung enthält.</param>
        <summary>
            Erstellt eine filterbedingung mithilfe des angegebenen logischen Operators für zwei filterbedingungen.
            </summary>
        <returns>Eine Zeichenfolge, die den kombinierten Filterausdruck enthält.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Copy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.CosmosDB.Table.TableQuery Copy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.CosmosDB.Table.TableQuery Copy() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableQuery.Copy" />
      <MemberSignature Language="VB.NET" Value="Public Function Copy () As TableQuery" />
      <MemberSignature Language="F#" Value="member this.Copy : unit -&gt; Microsoft.Azure.CosmosDB.Table.TableQuery" Usage="tableQuery.Copy " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableQuery</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Stellen Sie eine flache Kopie dieses Objekts TableQuery.
            </summary>
        <returns>Die neu erstellte flache Kopie.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FilterString">
      <MemberSignature Language="C#" Value="public string FilterString { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FilterString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableQuery.FilterString" />
      <MemberSignature Language="VB.NET" Value="Public Property FilterString As String" />
      <MemberSignature Language="F#" Value="member this.FilterString : string with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableQuery.FilterString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Filterausdruck für die Verwendung in der Tabellenabfrage.
            </summary>
        <value>Eine Zeichenfolge, die mit dem Filterausdruck in der Abfrage verwendet wird.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateFilterCondition">
      <MemberSignature Language="C#" Value="public static string GenerateFilterCondition (string propertyName, string operation, string givenValue);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GenerateFilterCondition(string propertyName, string operation, string givenValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableQuery.GenerateFilterCondition(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateFilterCondition (propertyName As String, operation As String, givenValue As String) As String" />
      <MemberSignature Language="F#" Value="static member GenerateFilterCondition : string * string * string -&gt; string" Usage="Microsoft.Azure.CosmosDB.Table.TableQuery.GenerateFilterCondition (propertyName, operation, givenValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="operation" Type="System.String" />
        <Parameter Name="givenValue" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="propertyName">Eine Zeichenfolge, die den Namen des zu vergleichenden Eigenschaft enthält.</param>
        <param name="operation">Eine Zeichenfolge, die die zu verwendenden Vergleichsoperator enthält.</param>
        <param name="givenValue">Eine Zeichenfolge mit dem Wert, der mit der Eigenschaft verglichen werden soll.</param>
        <summary>
            Generiert eine Zeichenfolge einer Eigenschaft eigenschaftsfilterbedingung für den Zeichenfolgenwert.
            </summary>
        <returns>Eine Zeichenfolge, die die formatierte filterbedingung enthält.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateFilterConditionForBinary">
      <MemberSignature Language="C#" Value="public static string GenerateFilterConditionForBinary (string propertyName, string operation, byte[] givenValue);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GenerateFilterConditionForBinary(string propertyName, string operation, unsigned int8[] givenValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableQuery.GenerateFilterConditionForBinary(System.String,System.String,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateFilterConditionForBinary (propertyName As String, operation As String, givenValue As Byte()) As String" />
      <MemberSignature Language="F#" Value="static member GenerateFilterConditionForBinary : string * string * byte[] -&gt; string" Usage="Microsoft.Azure.CosmosDB.Table.TableQuery.GenerateFilterConditionForBinary (propertyName, operation, givenValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="operation" Type="System.String" />
        <Parameter Name="givenValue" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="propertyName">Eine Zeichenfolge, die den Namen des zu vergleichenden Eigenschaft enthält.</param>
        <param name="operation">Eine Zeichenfolge, die die zu verwendenden Vergleichsoperator enthält.</param>
        <param name="givenValue">Ein Bytearray mit dem Wert, der mit der Eigenschaft verglichen werden soll.</param>
        <summary>
            Generiert eine Zeichenfolge einer Eigenschaft eigenschaftsfilterbedingung für den binären Wert.
            </summary>
        <returns>Eine Zeichenfolge, die die formatierte filterbedingung enthält.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateFilterConditionForBool">
      <MemberSignature Language="C#" Value="public static string GenerateFilterConditionForBool (string propertyName, string operation, bool givenValue);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GenerateFilterConditionForBool(string propertyName, string operation, bool givenValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableQuery.GenerateFilterConditionForBool(System.String,System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateFilterConditionForBool (propertyName As String, operation As String, givenValue As Boolean) As String" />
      <MemberSignature Language="F#" Value="static member GenerateFilterConditionForBool : string * string * bool -&gt; string" Usage="Microsoft.Azure.CosmosDB.Table.TableQuery.GenerateFilterConditionForBool (propertyName, operation, givenValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="operation" Type="System.String" />
        <Parameter Name="givenValue" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="propertyName">Eine Zeichenfolge, die den Namen des zu vergleichenden Eigenschaft enthält.</param>
        <param name="operation">Eine Zeichenfolge, die die zu verwendenden Vergleichsoperator enthält.</param>
        <param name="givenValue">Ein <c>Bool</c> mit dem Wert, der mit der Eigenschaft verglichen werden soll.</param>
        <summary>
            Generiert eine Zeichenfolge einer Eigenschaft eigenschaftsfilterbedingung für den booleschen Wert an.
            </summary>
        <returns>Eine Zeichenfolge, die die formatierte filterbedingung enthält.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateFilterConditionForDate">
      <MemberSignature Language="C#" Value="public static string GenerateFilterConditionForDate (string propertyName, string operation, DateTimeOffset givenValue);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GenerateFilterConditionForDate(string propertyName, string operation, valuetype System.DateTimeOffset givenValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableQuery.GenerateFilterConditionForDate(System.String,System.String,System.DateTimeOffset)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateFilterConditionForDate (propertyName As String, operation As String, givenValue As DateTimeOffset) As String" />
      <MemberSignature Language="F#" Value="static member GenerateFilterConditionForDate : string * string * DateTimeOffset -&gt; string" Usage="Microsoft.Azure.CosmosDB.Table.TableQuery.GenerateFilterConditionForDate (propertyName, operation, givenValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="operation" Type="System.String" />
        <Parameter Name="givenValue" Type="System.DateTimeOffset" />
      </Parameters>
      <Docs>
        <param name="propertyName">Eine Zeichenfolge, die den Namen des zu vergleichenden Eigenschaft enthält.</param>
        <param name="operation">Eine Zeichenfolge, die die zu verwendenden Vergleichsoperator enthält.</param>
        <param name="givenValue">Ein <see cref="T:System.DateTimeOffset" /> mit dem Wert, der mit der Eigenschaft verglichen werden soll.</param>
        <summary>
            Generiert eine Zeichenfolge eigenschaftsfilterbedingung für den <see cref="T:System.DateTimeOffset" /> Wert.
            </summary>
        <returns>Eine Zeichenfolge, die die formatierte filterbedingung enthält.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateFilterConditionForDouble">
      <MemberSignature Language="C#" Value="public static string GenerateFilterConditionForDouble (string propertyName, string operation, double givenValue);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GenerateFilterConditionForDouble(string propertyName, string operation, float64 givenValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableQuery.GenerateFilterConditionForDouble(System.String,System.String,System.Double)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateFilterConditionForDouble (propertyName As String, operation As String, givenValue As Double) As String" />
      <MemberSignature Language="F#" Value="static member GenerateFilterConditionForDouble : string * string * double -&gt; string" Usage="Microsoft.Azure.CosmosDB.Table.TableQuery.GenerateFilterConditionForDouble (propertyName, operation, givenValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="operation" Type="System.String" />
        <Parameter Name="givenValue" Type="System.Double" />
      </Parameters>
      <Docs>
        <param name="propertyName">Eine Zeichenfolge, die den Namen des zu vergleichenden Eigenschaft enthält.</param>
        <param name="operation">Eine Zeichenfolge, die die zu verwendenden Vergleichsoperator enthält.</param>
        <param name="givenValue">Ein <see cref="T:System.Double" /> mit dem Wert, der mit der Eigenschaft verglichen werden soll.</param>
        <summary>
            Generiert eine Zeichenfolge eigenschaftsfilterbedingung für den <see cref="T:System.Double" /> Wert.
            </summary>
        <returns>Eine Zeichenfolge, die die formatierte filterbedingung enthält.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateFilterConditionForGuid">
      <MemberSignature Language="C#" Value="public static string GenerateFilterConditionForGuid (string propertyName, string operation, Guid givenValue);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GenerateFilterConditionForGuid(string propertyName, string operation, valuetype System.Guid givenValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableQuery.GenerateFilterConditionForGuid(System.String,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateFilterConditionForGuid (propertyName As String, operation As String, givenValue As Guid) As String" />
      <MemberSignature Language="F#" Value="static member GenerateFilterConditionForGuid : string * string * Guid -&gt; string" Usage="Microsoft.Azure.CosmosDB.Table.TableQuery.GenerateFilterConditionForGuid (propertyName, operation, givenValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="operation" Type="System.String" />
        <Parameter Name="givenValue" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="propertyName">Eine Zeichenfolge, die den Namen des zu vergleichenden Eigenschaft enthält.</param>
        <param name="operation">Eine Zeichenfolge, die die zu verwendenden Vergleichsoperator enthält.</param>
        <param name="givenValue">Ein <see cref="T:System.Guid" /> mit dem Wert, der mit der Eigenschaft verglichen werden soll.</param>
        <summary>
            Generiert eine Zeichenfolge eigenschaftsfilterbedingung für den <see cref="T:System.Guid" /> Wert.
            </summary>
        <returns>Eine Zeichenfolge, die die formatierte filterbedingung enthält.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateFilterConditionForInt">
      <MemberSignature Language="C#" Value="public static string GenerateFilterConditionForInt (string propertyName, string operation, int givenValue);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GenerateFilterConditionForInt(string propertyName, string operation, int32 givenValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableQuery.GenerateFilterConditionForInt(System.String,System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateFilterConditionForInt (propertyName As String, operation As String, givenValue As Integer) As String" />
      <MemberSignature Language="F#" Value="static member GenerateFilterConditionForInt : string * string * int -&gt; string" Usage="Microsoft.Azure.CosmosDB.Table.TableQuery.GenerateFilterConditionForInt (propertyName, operation, givenValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="operation" Type="System.String" />
        <Parameter Name="givenValue" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="propertyName">Eine Zeichenfolge, die den Namen des zu vergleichenden Eigenschaft enthält.</param>
        <param name="operation">Eine Zeichenfolge, die die zu verwendenden Vergleichsoperator enthält.</param>
        <param name="givenValue">Ein <see cref="T:System.Int32" /> mit dem Wert, der mit der Eigenschaft verglichen werden soll.</param>
        <summary>
            Generiert eine Zeichenfolge eigenschaftsfilterbedingung für einen <see cref="T:System.Int32" /> Wert.
            </summary>
        <returns>Eine Zeichenfolge, die die formatierte filterbedingung enthält.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateFilterConditionForLong">
      <MemberSignature Language="C#" Value="public static string GenerateFilterConditionForLong (string propertyName, string operation, long givenValue);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GenerateFilterConditionForLong(string propertyName, string operation, int64 givenValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableQuery.GenerateFilterConditionForLong(System.String,System.String,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateFilterConditionForLong (propertyName As String, operation As String, givenValue As Long) As String" />
      <MemberSignature Language="F#" Value="static member GenerateFilterConditionForLong : string * string * int64 -&gt; string" Usage="Microsoft.Azure.CosmosDB.Table.TableQuery.GenerateFilterConditionForLong (propertyName, operation, givenValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="operation" Type="System.String" />
        <Parameter Name="givenValue" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="propertyName">Eine Zeichenfolge, die den Namen des zu vergleichenden Eigenschaft enthält.</param>
        <param name="operation">Eine Zeichenfolge, die die zu verwendenden Vergleichsoperator enthält.</param>
        <param name="givenValue">Ein <see cref="T:System.Int64" /> mit dem Wert, der mit der Eigenschaft verglichen werden soll.</param>
        <summary>
            Generiert eine Zeichenfolge eigenschaftsfilterbedingung für einen <see cref="T:System.Int64" /> Wert.
            </summary>
        <returns>Eine Zeichenfolge, die die formatierte filterbedingung enthält.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Project&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static T Project&lt;T&gt; (T entity, params string[] columns);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig !!T Project&lt;T&gt;(!!T entity, string[] columns) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableQuery.Project``1(``0,System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Project(Of T) (entity As T, ParamArray columns As String()) As T" />
      <MemberSignature Language="F#" Value="static member Project : 'T * string[] -&gt; 'T" Usage="Microsoft.Azure.CosmosDB.Table.TableQuery.Project (entity, columns)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="entity" Type="T" />
        <Parameter Name="columns" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <typeparam name="T">Der Entitätstyp der Abfrage.</typeparam>
        <param name="entity">Das Projekt aus der Entitätsinstanz.</param>
        <param name="columns">Eine Liste von Zeichenfolgenobjekten mit den Namen der Eigenschaften der Entität zurückgibt, wenn die Abfrage ausgeführt wird.</param>
        <summary>
            Gibt die Namen der Eigenschaften der Entität zurückgibt, wenn die Abfrage für die Tabelle ausgeführt wird. 
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> -Instanzensatz mit den Eigenschaften der Entität zurückgegeben.</returns>
        <remarks>Die Projekt-Klausel ist optional für eine Abfrage verwendet, um die Eigenschaften, die vom Server zurückgegebenen einzuschränken. Standardmäßig wird eine Abfrage alle Eigenschaften der Entität zurück.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Select">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.CosmosDB.Table.TableQuery Select (System.Collections.Generic.IList&lt;string&gt; columns);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.CosmosDB.Table.TableQuery Select(class System.Collections.Generic.IList`1&lt;string&gt; columns) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableQuery.Select(System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function Select (columns As IList(Of String)) As TableQuery" />
      <MemberSignature Language="F#" Value="member this.Select : System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.CosmosDB.Table.TableQuery" Usage="tableQuery.Select columns" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableQuery</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="columns" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="columns">Eine Liste von Zeichenfolgenobjekten mit den Eigenschaftsnamen der tabellenentitätseigenschaften zurückgibt, wenn die Abfrage ausgeführt wird.</param>
        <summary>
            Definiert die Eigenschaftsnamen der tabellenentitätseigenschaften, die bei der Ausführung der Tabellenabfrage zurückgegeben. 
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> -Instanzensatz mit tabellenentitätseigenschaften zurückgegeben.</returns>
        <remarks>Die select-Klausel ist optional für eine Table-Abfrage verwendet, um die vom Server zurückgegebenen Tabelleneigenschaften einzuschränken. Standardmäßig wird eine Abfrage alle Eigenschaften aus der Tabellenentität zurück.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SelectColumns">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; SelectColumns { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; SelectColumns" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableQuery.SelectColumns" />
      <MemberSignature Language="VB.NET" Value="Public Property SelectColumns As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.SelectColumns : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableQuery.SelectColumns" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Eigenschaftsnamen der tabellenentitätseigenschaften, die bei der Ausführung der Tabellenabfrage zurückgegeben.
            </summary>
        <value>Eine Liste von Zeichenfolgen, die mit den Eigenschaftsnamen der tabellenentitätseigenschaften zurückgibt, wenn die Abfrage ausgeführt wird.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Take">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.CosmosDB.Table.TableQuery Take (Nullable&lt;int&gt; take);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.CosmosDB.Table.TableQuery Take(valuetype System.Nullable`1&lt;int32&gt; take) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableQuery.Take(System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Function Take (take As Nullable(Of Integer)) As TableQuery" />
      <MemberSignature Language="F#" Value="member this.Take : Nullable&lt;int&gt; -&gt; Microsoft.Azure.CosmosDB.Table.TableQuery" Usage="tableQuery.Take take" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableQuery</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="take" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="take">Die maximale Anzahl von Entitäten für die Tabellenabfrage zurückgegeben werden soll.</param>
        <summary>
            Definiert die obere Grenze für die Anzahl der Entitäten, die die Abfrage zurückgibt.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> -Instanzensatz mit der Anzahl von Entitäten zurückgeben.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TakeCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TakeCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TakeCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableQuery.TakeCount" />
      <MemberSignature Language="VB.NET" Value="Public Property TakeCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TakeCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableQuery.TakeCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Anzahl der Entitäten, die von die Tabellenabfrage zurückgegeben wird. 
            </summary>
        <value>Die maximale Anzahl von Entitäten für die Tabellenabfrage zurückgegeben werden soll.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Where">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.CosmosDB.Table.TableQuery Where (string filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.CosmosDB.Table.TableQuery Where(string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableQuery.Where(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function Where (filter As String) As TableQuery" />
      <MemberSignature Language="F#" Value="member this.Where : string -&gt; Microsoft.Azure.CosmosDB.Table.TableQuery" Usage="tableQuery.Where filter" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableQuery</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="filter">Eine Zeichenfolge, die mit dem Filterausdruck für die Tabellenabfrage angewendet wird.</param>
        <summary>
            Definiert einen Filterausdruck für die Tabellenabfrage. Nur Entitäten, die den angegebenen Filterausdruck entsprechen, werden von der Abfrage zurückgegeben. 
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> -Instanzensatz mit dem Filter für Entitäten zurückgeben.</returns>
        <remarks>Festlegen eines Filterausdrucks ist optional. Standardmäßig werden alle Entitäten in der Tabelle zurückgegeben, wenn kein Filterausdruck in der Tabellenabfrage angegeben ist.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>