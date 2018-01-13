<Type Name="TaskDependencies" FullName="Microsoft.Azure.Batch.TaskDependencies">
  <TypeSignature Language="C#" Value="public class TaskDependencies" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskDependencies extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.TaskDependencies" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskDependencies" />
  <TypeSignature Language="F#" Value="type TaskDependencies = class&#xA;    interface ITransportObjectProvider&lt;TaskDependencies&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Gibt alle Abhängigkeiten von einer Aufgabe an. Jede Aufgabe, die explizit angegeben wird oder innerhalb einer Abhängigkeit Bereich abgeschlossen werden muss, bevor der abhängige Task geplant wird.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskDependencies (System.Collections.Generic.IEnumerable&lt;string&gt; taskIds, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.TaskIdRange&gt; taskIdRanges);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;string&gt; taskIds, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.TaskIdRange&gt; taskIdRanges) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.TaskDependencies.#ctor(System.Collections.Generic.IEnumerable{System.String},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.TaskIdRange})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (taskIds As IEnumerable(Of String), taskIdRanges As IEnumerable(Of TaskIdRange))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.TaskDependencies : seq&lt;string&gt; * seq&lt;Microsoft.Azure.Batch.TaskIdRange&gt; -&gt; Microsoft.Azure.Batch.TaskDependencies" Usage="new Microsoft.Azure.Batch.TaskDependencies (taskIds, taskIdRanges)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="taskIds" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="taskIdRanges" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.TaskIdRange&gt;" />
      </Parameters>
      <Docs>
        <param name="taskIds">Die Liste der Aufgaben-Ids, die abgeschlossen werden muss, bevor diese Aufgabe geplant werden kann. NULL wird als eine leere Liste behandelt.</param>
        <param name="taskIdRanges">Die Liste der Task-Bereiche, die abgeschlossen werden muss, bevor diese Aufgabe geplant werden kann. NULL wird als eine leere Liste behandelt.</param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.TaskDependencies" />-Klasse.
            </summary>
        <remarks>Dieser Konstruktor stellt die allgemeinste Methode zum Initialisieren eines TaskDependencies-Objekts.
            In der Praxis werden die meisten Abhängigkeiten auf eine einzelne Aufgabe, eine Liste der Aufgaben-Ids oder einem einzelnen Bereich von Aufgaben. Sie können diese Abhängigkeiten deutlich mit Ausdrücken <see cref="M:Microsoft.Azure.Batch.TaskDependencies.OnId(System.String)" />, <see cref="M:Microsoft.Azure.Batch.TaskDependencies.OnIds(System.String[])" />, <see cref="M:Microsoft.Azure.Batch.TaskDependencies.OnTasks(Microsoft.Azure.Batch.CloudTask[])" />, und <see cref="M:Microsoft.Azure.Batch.TaskDependencies.OnIdRange(System.Int32,System.Int32)" /> Methoden.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnId">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.TaskDependencies OnId (string id);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.TaskDependencies OnId(string id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.TaskDependencies.OnId(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function OnId (id As String) As TaskDependencies" />
      <MemberSignature Language="F#" Value="static member OnId : string -&gt; Microsoft.Azure.Batch.TaskDependencies" Usage="Microsoft.Azure.Batch.TaskDependencies.OnId id" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.TaskDependencies</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">Die Aufgabe, die von abhängig sind.</param>
        <summary>
            Ruft eine <see cref="T:Microsoft.Azure.Batch.TaskDependencies" /> , die Abhängigkeit auf eine einzelne Aufgabe darstellt.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Batch.TaskDependencies" /> , die Abhängigkeit auf eine einzelne Aufgabe darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnIdRange">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.TaskDependencies OnIdRange (int start, int end);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.TaskDependencies OnIdRange(int32 start, int32 end) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.TaskDependencies.OnIdRange(System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function OnIdRange (start As Integer, end As Integer) As TaskDependencies" />
      <MemberSignature Language="F#" Value="static member OnIdRange : int * int -&gt; Microsoft.Azure.Batch.TaskDependencies" Usage="Microsoft.Azure.Batch.TaskDependencies.OnIdRange (start, end)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.TaskDependencies</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="start" Type="System.Int32" />
        <Parameter Name="end" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="start">Der erste Task-Id im Bereich von abhängen.</param>
        <param name="end">Die letzte Task-Id im Bereich von abhängen.</param>
        <summary>
            Ruft eine <see cref="T:Microsoft.Azure.Batch.TaskDependencies" /> , die Abhängigkeit auf einen Bereich von Aufgaben-Ids darstellt.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Batch.TaskDependencies" /> , die Abhängigkeit von den angegebenen Bereich von Aufgaben darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnIds">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.TaskDependencies OnIds (System.Collections.Generic.IEnumerable&lt;string&gt; ids);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.TaskDependencies OnIds(class System.Collections.Generic.IEnumerable`1&lt;string&gt; ids) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.TaskDependencies.OnIds(System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function OnIds (ids As IEnumerable(Of String)) As TaskDependencies" />
      <MemberSignature Language="F#" Value="static member OnIds : seq&lt;string&gt; -&gt; Microsoft.Azure.Batch.TaskDependencies" Usage="Microsoft.Azure.Batch.TaskDependencies.OnIds ids" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.TaskDependencies</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ids" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="ids">Die Aufgaben von abhängen.</param>
        <summary>
            Ruft eine <see cref="T:Microsoft.Azure.Batch.TaskDependencies" /> , die Abhängigkeit auf eine Liste der Aufgaben-Ids darstellt.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Batch.TaskDependencies" /> , die Abhängigkeit von der angegebenen Aufgaben darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnIds">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.TaskDependencies OnIds (params string[] ids);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.TaskDependencies OnIds(string[] ids) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.TaskDependencies.OnIds(System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function OnIds (ParamArray ids As String()) As TaskDependencies" />
      <MemberSignature Language="F#" Value="static member OnIds : string[] -&gt; Microsoft.Azure.Batch.TaskDependencies" Usage="Microsoft.Azure.Batch.TaskDependencies.OnIds ids" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.TaskDependencies</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ids" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="ids">Die Aufgaben von abhängen.</param>
        <summary>
            Ruft eine <see cref="T:Microsoft.Azure.Batch.TaskDependencies" /> , die Abhängigkeit auf eine Liste der Aufgaben-Ids darstellt.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Batch.TaskDependencies" /> , die Abhängigkeit von der angegebenen Aufgaben darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnTasks">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.TaskDependencies OnTasks (params Microsoft.Azure.Batch.CloudTask[] tasks);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.TaskDependencies OnTasks(class Microsoft.Azure.Batch.CloudTask[] tasks) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.TaskDependencies.OnTasks(Microsoft.Azure.Batch.CloudTask[])" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function OnTasks (ParamArray tasks As CloudTask()) As TaskDependencies" />
      <MemberSignature Language="F#" Value="static member OnTasks : Microsoft.Azure.Batch.CloudTask[] -&gt; Microsoft.Azure.Batch.TaskDependencies" Usage="Microsoft.Azure.Batch.TaskDependencies.OnTasks tasks" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.TaskDependencies</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tasks" Type="Microsoft.Azure.Batch.CloudTask[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="tasks">Die Aufgaben von abhängen.</param>
        <summary>
            Ruft eine <see cref="T:Microsoft.Azure.Batch.TaskDependencies" /> , die Abhängigkeit auf eine Liste von Aufgaben darstellt.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Batch.TaskDependencies" /> , die Abhängigkeit von der angegebenen Aufgaben darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnTasks">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.TaskDependencies OnTasks (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt; tasks);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.TaskDependencies OnTasks(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.CloudTask&gt; tasks) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.TaskDependencies.OnTasks(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function OnTasks (tasks As IEnumerable(Of CloudTask)) As TaskDependencies" />
      <MemberSignature Language="F#" Value="static member OnTasks : seq&lt;Microsoft.Azure.Batch.CloudTask&gt; -&gt; Microsoft.Azure.Batch.TaskDependencies" Usage="Microsoft.Azure.Batch.TaskDependencies.OnTasks tasks" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.TaskDependencies</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tasks" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt;" />
      </Parameters>
      <Docs>
        <param name="tasks">Die Aufgaben von abhängen.</param>
        <summary>
            Ruft eine <see cref="T:Microsoft.Azure.Batch.TaskDependencies" /> , die Abhängigkeit auf eine Liste von Aufgaben darstellt.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Batch.TaskDependencies" /> , die Abhängigkeit von der angegebenen Aufgaben darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskIdRanges">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.TaskIdRange&gt; TaskIdRanges { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Batch.TaskIdRange&gt; TaskIdRanges" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskDependencies.TaskIdRanges" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TaskIdRanges As IReadOnlyList(Of TaskIdRange)" />
      <MemberSignature Language="F#" Value="member this.TaskIdRanges : System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.TaskIdRange&gt;" Usage="Microsoft.Azure.Batch.TaskDependencies.TaskIdRanges" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.TaskIdRange&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Liste der Aufgaben-IDs, die von dieser Aufgabe abhängig ist. Alle Aufgaben in dieser Liste müssen erfolgreich abgeschlossen, bevor der abhängige Task geplant werden kann.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskIds">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;string&gt; TaskIds { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;string&gt; TaskIds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskDependencies.TaskIds" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TaskIds As IReadOnlyList(Of String)" />
      <MemberSignature Language="F#" Value="member this.TaskIds : System.Collections.Generic.IReadOnlyList&lt;string&gt;" Usage="Microsoft.Azure.Batch.TaskDependencies.TaskIds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Liste der Task-ID-Bereiche, denen von dieser Aufgabe abhängig ist. Alle Aufgaben in allen Bereichen müssen erfolgreich abgeschlossen, bevor der abhängige Task geplant werden kann.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>