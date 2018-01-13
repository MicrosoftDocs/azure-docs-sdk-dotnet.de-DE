<Type Name="JobOutputKind" FullName="Microsoft.Azure.Batch.Conventions.Files.JobOutputKind">
  <TypeSignature Language="C#" Value="public sealed class JobOutputKind : IEquatable&lt;Microsoft.Azure.Batch.Conventions.Files.JobOutputKind&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit JobOutputKind extends System.Object implements class System.IEquatable`1&lt;class Microsoft.Azure.Batch.Conventions.Files.JobOutputKind&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class JobOutputKind&#xA;Implements IEquatable(Of JobOutputKind)" />
  <TypeSignature Language="F#" Value="type JobOutputKind = class&#xA;    interface IEquatable&lt;JobOutputKind&gt;&#xA;    interface IOutputKind" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IEquatable&lt;Microsoft.Azure.Batch.Conventions.Files.JobOutputKind&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Stellt eine Kategorie von auftragsausgaben, z. B. die Hauptauftrags-Ausgabe oder eine Vorschau des Auftrags-Ausgabe dar.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Custom">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Conventions.Files.JobOutputKind Custom (string text);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Conventions.Files.JobOutputKind Custom(string text) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.Custom(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Custom (text As String) As JobOutputKind" />
      <MemberSignature Language="F#" Value="static member Custom : string -&gt; Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" Usage="Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.Custom text" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Conventions.Files.JobOutputKind</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="text" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="text">Ein Textbezeichner für die benutzerdefinierte JobOutputKind.</param>
        <summary>
            Ruft eine <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" /> , die eine benutzerdefinierte Kategorie von auftragsausgaben darstellt.
            </summary>
        <returns>Eine JobOutputKind mit dem angegebenen Text.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="text" /> ist NULL.</exception>
        <exception cref="T:System.ArgumentException">
          <paramref name="text" /> ist leer.</exception>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.Azure.Batch.Conventions.Files.JobOutputKind other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(class Microsoft.Azure.Batch.Conventions.Files.JobOutputKind other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.Equals(Microsoft.Azure.Batch.Conventions.Files.JobOutputKind)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As JobOutputKind) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.Azure.Batch.Conventions.Files.JobOutputKind -&gt; bool" Usage="jobOutputKind.Equals other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IEquatable`1.Equals(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" />
      </Parameters>
      <Docs>
        <param name="other">Die JobOutputKind dieser Instanz verglichen werden soll.</param>
        <summary>
            Determinates, ob diese Instanz und ein anderes angegebenes <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" /> denselben Wert haben.
            </summary>
        <returns>True, wenn der Wert des der <paramref name="other" /> Parameter ist der Wert dieser Instanz entspricht, andernfalls "false".</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="jobOutputKind.Equals obj" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj">Das Objekt, das mit dem aktuellen Objekt verglichen werden soll.</param>
        <summary>
            Bestimmt, ob das angegebene Objekt mit dem aktuellen Objekt identisch ist.
            </summary>
        <returns>True, wenn das angegebene Objekt mit dem aktuellen Objekt identisch ist. andernfalls "false".</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="jobOutputKind.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Gibt den Hashcode für diesen <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" /> zurück.
            </summary>
        <returns>Ein 32-Bit-Hashcode als ganze Zahl mit Vorzeichen.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobOutput">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Batch.Conventions.Files.JobOutputKind JobOutput;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Batch.Conventions.Files.JobOutputKind JobOutput" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobOutput" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly JobOutput As JobOutputKind " />
      <MemberSignature Language="F#" Value=" staticval mutable JobOutput : Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" Usage="Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobOutput" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Conventions.Files.JobOutputKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ein <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" /> , die wichtigsten Ausgabe eines Auftrags darstellt.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobPreview">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Batch.Conventions.Files.JobOutputKind JobPreview;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Batch.Conventions.Files.JobOutputKind JobPreview" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobPreview" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly JobPreview As JobOutputKind " />
      <MemberSignature Language="F#" Value=" staticval mutable JobPreview : Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" Usage="Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobPreview" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Conventions.Files.JobOutputKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ein <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" /> , die eine Vorschau des Auftrags-Ausgabe darstellt.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Equality">
      <MemberSignature Language="C#" Value="public static bool operator == (Microsoft.Azure.Batch.Conventions.Files.JobOutputKind x, Microsoft.Azure.Batch.Conventions.Files.JobOutputKind y);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_Equality(class Microsoft.Azure.Batch.Conventions.Files.JobOutputKind x, class Microsoft.Azure.Batch.Conventions.Files.JobOutputKind y) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.op_Equality(Microsoft.Azure.Batch.Conventions.Files.JobOutputKind,Microsoft.Azure.Batch.Conventions.Files.JobOutputKind)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator == (x As JobOutputKind, y As JobOutputKind) As Boolean" />
      <MemberSignature Language="F#" Value="static member ( = ) : Microsoft.Azure.Batch.Conventions.Files.JobOutputKind * Microsoft.Azure.Batch.Conventions.Files.JobOutputKind -&gt; bool" Usage="x = y" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="x" Type="Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" />
        <Parameter Name="y" Type="Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" />
      </Parameters>
      <Docs>
        <param name="x">Die erste JobOutputKind, verglichen werden soll.</param>
        <param name="y">Die zweite JobOutputKind, verglichen werden soll.</param>
        <summary>
            Bestimmt, ob zwei angegebene <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" /> Instanzen den gleichen Wert aufweisen.
            </summary>
        <returns>True, wenn der Wert der <paramref name="x" /> entspricht der Wert des <paramref name="y" />, andernfalls "false".</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Inequality">
      <MemberSignature Language="C#" Value="public static bool operator != (Microsoft.Azure.Batch.Conventions.Files.JobOutputKind x, Microsoft.Azure.Batch.Conventions.Files.JobOutputKind y);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_Inequality(class Microsoft.Azure.Batch.Conventions.Files.JobOutputKind x, class Microsoft.Azure.Batch.Conventions.Files.JobOutputKind y) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.op_Inequality(Microsoft.Azure.Batch.Conventions.Files.JobOutputKind,Microsoft.Azure.Batch.Conventions.Files.JobOutputKind)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator != (x As JobOutputKind, y As JobOutputKind) As Boolean" />
      <MemberSignature Language="F#" Value="static member op_Inequality : Microsoft.Azure.Batch.Conventions.Files.JobOutputKind * Microsoft.Azure.Batch.Conventions.Files.JobOutputKind -&gt; bool" Usage="Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.op_Inequality (x, y)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="x" Type="Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" />
        <Parameter Name="y" Type="Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" />
      </Parameters>
      <Docs>
        <param name="x">Die erste JobOutputKind, verglichen werden soll.</param>
        <param name="y">Die zweite JobOutputKind, verglichen werden soll.</param>
        <summary>
            Bestimmt, ob zwei angegebene <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" /> Instanzen über unterschiedliche Werte verfügen.
            </summary>
        <returns>True, wenn der Wert der <paramref name="x" /> unterscheidet sich vom Wert der <paramref name="y" />, andernfalls "false".</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="jobOutputKind.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Gibt eine Zeichenfolge zurück, die das aktuelle Objekt darstellt.
            </summary>
        <returns>Eine Textdarstellung der <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>