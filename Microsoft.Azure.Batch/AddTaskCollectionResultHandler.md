<Type Name="AddTaskCollectionResultHandler" FullName="Microsoft.Azure.Batch.AddTaskCollectionResultHandler">
  <TypeSignature Language="C#" Value="public class AddTaskCollectionResultHandler : Microsoft.Azure.Batch.BatchClientBehavior" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AddTaskCollectionResultHandler extends Microsoft.Azure.Batch.BatchClientBehavior" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.AddTaskCollectionResultHandler" />
  <TypeSignature Language="VB.NET" Value="Public Class AddTaskCollectionResultHandler&#xA;Inherits BatchClientBehavior" />
  <TypeSignature Language="F#" Value="type AddTaskCollectionResultHandler = class&#xA;    inherit BatchClientBehavior" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Batch.BatchClientBehavior</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Ein <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> die Sie verwenden können, um anzugeben, unter welche einen Vorgang zum Hinzufügen von mehreren Aufgaben, die einen Auftrag sollte wiederholen Bedingungen, beenden oder als erfolgreich betrachtet werden.
            </summary>
    <remarks>Sie müssen nicht auf dieses Verhalten explizit angeben; Wenn Sie nicht der Fall ist, wird ein Standardverhalten verwendet.  Dieses Verhalten wird verwendet, die <see cref="M:Microsoft.Azure.Batch.AddTaskCollectionResultHandler.DefaultAddTaskCollectionResultHandler(Microsoft.Azure.Batch.AddTaskResult,System.Threading.CancellationToken)" /> Kriterien.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AddTaskCollectionResultHandler (Func&lt;Microsoft.Azure.Batch.AddTaskResult,System.Threading.CancellationToken,Microsoft.Azure.Batch.AddTaskResultStatus&gt; resultHandler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Func`3&lt;class Microsoft.Azure.Batch.AddTaskResult, valuetype System.Threading.CancellationToken, valuetype Microsoft.Azure.Batch.AddTaskResultStatus&gt; resultHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.AddTaskCollectionResultHandler.#ctor(System.Func{Microsoft.Azure.Batch.AddTaskResult,System.Threading.CancellationToken,Microsoft.Azure.Batch.AddTaskResultStatus})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (resultHandler As Func(Of AddTaskResult, CancellationToken, AddTaskResultStatus))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.AddTaskCollectionResultHandler : Func&lt;Microsoft.Azure.Batch.AddTaskResult, System.Threading.CancellationToken, Microsoft.Azure.Batch.AddTaskResultStatus&gt; -&gt; Microsoft.Azure.Batch.AddTaskCollectionResultHandler" Usage="new Microsoft.Azure.Batch.AddTaskCollectionResultHandler resultHandler" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="resultHandler" Type="System.Func&lt;Microsoft.Azure.Batch.AddTaskResult,System.Threading.CancellationToken,Microsoft.Azure.Batch.AddTaskResultStatus&gt;" />
      </Parameters>
      <Docs>
        <param name="resultHandler">Eine Funktion, die definiert, ob eine bestimmte Aufgabe hinzufügen-Operation erfolgreich oder nicht erfolgreich betrachtet wird, und gibt an, ob die Verarbeitung wiederholt werden kann.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Batch.AddTaskCollectionResultHandler" /> Klasse mit dem angegebenen Ergebnis Handlerfunktion.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultAddTaskCollectionResultHandler">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.AddTaskResultStatus DefaultAddTaskCollectionResultHandler (Microsoft.Azure.Batch.AddTaskResult addTaskResult, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig valuetype Microsoft.Azure.Batch.AddTaskResultStatus DefaultAddTaskCollectionResultHandler(class Microsoft.Azure.Batch.AddTaskResult addTaskResult, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.AddTaskCollectionResultHandler.DefaultAddTaskCollectionResultHandler(Microsoft.Azure.Batch.AddTaskResult,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DefaultAddTaskCollectionResultHandler : Microsoft.Azure.Batch.AddTaskResult * System.Threading.CancellationToken -&gt; Microsoft.Azure.Batch.AddTaskResultStatus" Usage="Microsoft.Azure.Batch.AddTaskCollectionResultHandler.DefaultAddTaskCollectionResultHandler (addTaskResult, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.AddTaskResultStatus</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addTaskResult" Type="Microsoft.Azure.Batch.AddTaskResult" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="addTaskResult">Das Ergebnis einer einzelnen Aufgabe hinzufügen-Vorgang.</param>
        <param name="cancellationToken">Das Abbruchtoken, das dem Vorgang AddTaskCollection zugeordnet.</param>
        <summary>
            Der Standardhandler-Ergebnis für die <see cref="T:Microsoft.Azure.Batch.AddTaskCollectionResultHandler" /> Verhalten. Dieser Handler behandelt Erfolg und Fehler von "TaskExists" erfolgreich ausgeführt wurde, wiederholt Serverfehler (HTTP-5xx) und löst <see cref="T:Microsoft.Azure.Batch.AddTaskCollectionTerminatedException" /> auf Client-Fehler (HTTP-4xx).
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Batch.AddTaskResultStatus" /> gibt an, ob die <paramref name="addTaskResult" /> wird als Erfolg oder erfordern eine Wiederholung klassifiziert.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResultHandler">
      <MemberSignature Language="C#" Value="public Func&lt;Microsoft.Azure.Batch.AddTaskResult,System.Threading.CancellationToken,Microsoft.Azure.Batch.AddTaskResultStatus&gt; ResultHandler { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`3&lt;class Microsoft.Azure.Batch.AddTaskResult, valuetype System.Threading.CancellationToken, valuetype Microsoft.Azure.Batch.AddTaskResultStatus&gt; ResultHandler" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.AddTaskCollectionResultHandler.ResultHandler" />
      <MemberSignature Language="VB.NET" Value="Public Property ResultHandler As Func(Of AddTaskResult, CancellationToken, AddTaskResultStatus)" />
      <MemberSignature Language="F#" Value="member this.ResultHandler : Func&lt;Microsoft.Azure.Batch.AddTaskResult, System.Threading.CancellationToken, Microsoft.Azure.Batch.AddTaskResultStatus&gt; with get, set" Usage="Microsoft.Azure.Batch.AddTaskCollectionResultHandler.ResultHandler" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;Microsoft.Azure.Batch.AddTaskResult,System.Threading.CancellationToken,Microsoft.Azure.Batch.AddTaskResultStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Funktion, die definiert, ob eine bestimmte Aufgabe hinzufügen-Operation erfolgreich oder nicht erfolgreich betrachtet wird, und gibt an, ob die Verarbeitung wiederholt werden kann.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>