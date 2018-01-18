<Type Name="AutoScaleRun" FullName="Microsoft.Azure.Batch.AutoScaleRun">
  <TypeSignature Language="C#" Value="public class AutoScaleRun" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AutoScaleRun extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.AutoScaleRun" />
  <TypeSignature Language="VB.NET" Value="Public Class AutoScaleRun" />
  <TypeSignature Language="F#" Value="type AutoScaleRun = class&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            <span data-ttu-id="2b418-101">Die Ergebnisse und Fehler von einer Evaluation oder Ausführung einer Formel für die automatische Skalierung Pool.</span><span class="sxs-lookup"><span data-stu-id="2b418-101">The results and errors from an evaluation or execution of a pool autoscale formula.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Error">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.AutoScaleRunError Error { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.AutoScaleRunError Error" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.AutoScaleRun.Error" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Error As AutoScaleRunError" />
      <MemberSignature Language="F#" Value="member this.Error : Microsoft.Azure.Batch.AutoScaleRunError" Usage="Microsoft.Azure.Batch.AutoScaleRun.Error" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.AutoScaleRunError</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2b418-102">Ruft Details zu den aufgetretenen Fehler Auswerten der Formel für automatische Skalierung für den Pool, wenn die Auswertung nicht erfolgreich war.</span><span class="sxs-lookup"><span data-stu-id="2b418-102">Gets details of the error encountered evaluating the autoscale formula on the pool, if the evaluation was unsuccessful.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Results">
      <MemberSignature Language="C#" Value="public string Results { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Results" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.AutoScaleRun.Results" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Results As String" />
      <MemberSignature Language="F#" Value="member this.Results : string" Usage="Microsoft.Azure.Batch.AutoScaleRun.Results" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2b418-103">Ruft die endgültigen Werte aller Variablen, die bei der Auswertung der Formel für automatische Skalierung verwendet.</span><span class="sxs-lookup"><span data-stu-id="2b418-103">Gets the final values of all variables used in the evaluation of the autoscale formula.</span></span> <span data-ttu-id="2b418-104">Jeder Wert der Variablen wird zurückgegeben, in der Form $variable = Value, und die Variablen werden durch Semikolons getrennt.</span><span class="sxs-lookup"><span data-stu-id="2b418-104">Each variable value is returned in the form $variable=value, and variables are separated by semicolons.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timestamp">
      <MemberSignature Language="C#" Value="public DateTime Timestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime Timestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.AutoScaleRun.Timestamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Timestamp As DateTime" />
      <MemberSignature Language="F#" Value="member this.Timestamp : DateTime" Usage="Microsoft.Azure.Batch.AutoScaleRun.Timestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2b418-105">Ruft den Zeitpunkt, an dem die Formel für automatische Skalierung zuletzt bewertet wurde.</span><span class="sxs-lookup"><span data-stu-id="2b418-105">Gets the time at which the autoscale formula was last evaluated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>